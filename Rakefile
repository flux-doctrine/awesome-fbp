require 'json'
require 'pathname'
require 'stringio'
require 'yaml'

PROJECTS = Dir['projects/**/*.yaml'].sort_by do |path|
  path.delete_prefix('projects/').delete_suffix('.yaml')
end.freeze

SHOWCASE = Dir['showcase/**/*.yaml'].sort_by do |path|
  path.delete_prefix('showcase/').delete_suffix('.yaml')
end.freeze

namespace :list do
  task :people => Dir['people/*.md'].sort do |t|
    t.prerequisites.each do |path|
      handle = Pathname(path).to_s.delete_prefix('people/').delete_suffix('.md')
      puts "[@#{handle}](https://github.com/#{handle}),"
    end
  end
end

task default: %w(projects.json projects.md showcase.json showcase.md)

file 'projects.json': PROJECTS do |t|
  File.open(t.name, 'w') do |out|
    out.puts generate_json(t.prerequisites)
  end
end

file 'projects.md': PROJECTS do |t|
  File.open(t.name, 'w') do |out|
    out.puts generate_markdown(t.prerequisites)
  end
end

file 'showcase.json': SHOWCASE do |t|
  File.open(t.name, 'w') do |out|
    out.puts generate_json(t.prerequisites)
  end
end

file 'showcase.md': SHOWCASE do |t|
  File.open(t.name, 'w') do |out|
    out.puts generate_markdown(t.prerequisites)
  end
end

def generate_markdown(input_paths)
  StringIO.open do |out|
    out.puts "| Project | Summary | Author | Language | License | Updated | Links |"
    out.puts "| :------ | :------ | :----- | :------- | :------ | :------ | :---- |"
    load_projects(input_paths).each do |project|
      project_authors = project[:authors].map { it.delete_prefix('https://github.com/') }
      project_author = "[@#{project_authors.first}](https://github.com/#{project_authors.first})"
      project_link = "[#{project[:label]}](#{project[:links].first})"
      project_links = project[:links].map do |url|
        emoji = case
          when url.start_with?('https://github.com') then ':octocat:'
          when %w(crates.io hex.pm).any? { url.start_with?("https://#{it}") } then '📦'
          when %w(docs.rs hexdocs.pm).any? { url.start_with?("https://#{it}") } then ':book:'
          else ':house:'
        end
        "[#{emoji}](#{url})"
      end
      out.puts "| " + [
        project_link,
        project[:summary].strip,
        project_author,
        project[:language] || 'TBD',
        (project[:license] || 'Unknown').split('-').first,
        project[:updated] || '',
        project_links.join(' '),
      ].join(" | ") + " |"
    end
    out.string
  end
end

def generate_json(input_paths)
  JSON.pretty_unparse(load_projects(input_paths))
end

def load_projects(input_paths)
  input_paths.map do |input_path|
    YAML.safe_load(File.read(input_path), symbolize_names: true)
  end
end
