# Awesome Flow-Based Programming (FBP)

This is a community knowledge base for [flow-based programming (FBP)](https://grokipedia.com/page/Flow-based_programming).

![The flow-based programming paradigm](./paradigm.png)

<br/>

<sub>

[[Reading](#links)] |
[[Showcase](#showcase)] |
[[Reference](#reference)] |
[[Community](#community)] |
[[Credits](#credits)]

</sub>

## Reading

### Encyclopedias

Flow-based programming on [Wikipedia](https://en.wikipedia.org/wiki/Flow-based_programming),
[Grokipedia](https://grokipedia.com/page/Flow-based_programming),
[WikiWikiWeb](https://wiki.c2.com/?FlowBasedProgramming),
[Python Wiki](https://wiki.python.org/moin/FlowBasedProgramming), and
[Tcl Wiki](https://wiki.tcl-lang.org/page/flow-based+programming).

### Articles

- [J. Paul Morrison's Flow-Based Programming Website](https://jpaulm.github.io/fbp/)
  by [@jpaulm](https://github.com/jpaulm)
- [Flow-Based Programming: Seminal Texts & Theoretical Foundations](https://repolex.ai/blog/2025/12/10/fbp-seminal-texts/)
  (2026) by [@goodlux](https://github.com/goodlux) et al.
- [Flow-Based Programming, a Way for AI and Humans to Develop Together](https://bergie.iki.fi/blog/fbp-ai-human-collaboration/)
  (2023) by [@bergie](https://github.com/bergie)
- [Flowmaps: Mapping Clojure core.async Flows Through Time & Space](https://www.ryrob.es/flowmaps-mapping-clojure-flows-space-time/)
  (2023) by [@ryrobes](https://github.com/ryrobes)
- [The State of Flow-Based Programming](https://blog.kodigy.com/post/state-of-flow-based-programming/)
  (2022) by [@trustmaster](https://github.com/trustmaster)
- [Tom Young's FBP Spreadsheet](https://docs.google.com/spreadsheets/d/1n_wc2OoX4IOAACi5Iyt5HORs4nVhuTcYLxQkMK0u_08/edit)
  (2021) by [@tyoung3](https://github.com/tyoung3)
- [What the Hell Is Flow-Based Programming?](https://medium.com/bitspark/what-the-hell-is-flow-based-programming-d9e88a6a7265)
  (2018) by [@jm9e](https://github.com/jm9e)

## Showcase

| Project | Summary | Author | Language | License | Updated | Links |
| :------ | :------ | :----- | :------- | :------ | :------ | :---- |
| [Apache NiFi](https://github.com/apache/nifi) | Mature ETL workflow system based on FBP. | [@apache](https://github.com/apache) | Java | Apache | 2026 | [:octocat:](https://github.com/apache/nifi) [:house:](https://nifi.apache.org) |
| [Async-Flow](https://github.com/artob/async-flow) | Async FBP core abstractions for Tokio. | [@artob](https://github.com/artob) | Rust | Unlicense | 2026 | [:octocat:](https://github.com/artob/async-flow) [📦](https://crates.io/crates/async-flow) [:book:](https://docs.rs/async-flow) [:house:](https://async-flow.rs) |
| [CppFBP](https://github.com/jpaulm/cppfbp) | Classical FBP implementation for C++. | [@jpaulm](https://github.com/jpaulm) | C, C++ | Artistic | 2021 | [:octocat:](https://github.com/jpaulm/cppfbp) |
| [CsharpFBP](https://github.com/jpaulm/csharpfbp) | Classical FBP implementation for C#. | [@jpaulm](https://github.com/jpaulm) | C# | Artistic | 2021 | [:octocat:](https://github.com/jpaulm/csharpfbp) |
| [Flowex](https://github.com/antonmi/flowex) | FBP/ROP framework based on GenStage. | [@antonmi](https://github.com/antonmi) | Elixir | Apache | 2021 | [:octocat:](https://github.com/antonmi/flowex) [📦](https://hex.pm/packages/flowex) [:book:](https://hexdocs.pm/flowex) |
| [Flows.rs](https://github.com/artob/flows.rs) | Reusable FBP building blocks for Tokio. | [@artob](https://github.com/artob) | Rust | Unlicense | 2026 | [:octocat:](https://github.com/artob/flows.rs) [📦](https://crates.io/crates/flows) [:book:](https://docs.rs/flows) [:house:](https://flows.rs) |
| [GoFBP](https://github.com/jpaulm/gofbp) | Classical FBP implementation for Go. | [@jpaulm](https://github.com/jpaulm) | Go | Unknown | 2022 | [:octocat:](https://github.com/jpaulm/gofbp) |
| [JavaFBP](https://github.com/jpaulm/javafbp) | Classical FBP implementation for Java. | [@jpaulm](https://github.com/jpaulm) | Java | LGPL | 2022 | [:octocat:](https://github.com/jpaulm/javafbp) |
| [JSFBP](https://github.com/jpaulm/jsfbp) | Classical FBP implementation for JavaScript. | [@jpaulm](https://github.com/jpaulm) | JavaScript | MIT | 2021 | [:octocat:](https://github.com/jpaulm/jsfbp) |
| [Node-RED](https://github.com/node-red/node-red) | Popular low-code IDE for event-driven apps. | [@knolleary](https://github.com/knolleary) | JavaScript | Apache | 2026 | [:octocat:](https://github.com/node-red/node-red) [:house:](https://nodered.org) |
| [NoFlo](https://github.com/noflo/noflo) | Popular FBP-inspired runtime for Node.js. | [@bergie](https://github.com/bergie) | JavaScript | MIT | 2024 | [:octocat:](https://github.com/noflo/noflo) [:house:](https://noflojs.org) |
| [Protoflow](https://github.com/asimov-platform/protoflow) | Thread-based FBP using Protocol Buffers. | [@artob](https://github.com/artob) | Rust | Unlicense | 2025 | [:octocat:](https://github.com/asimov-platform/protoflow) [📦](https://crates.io/crates/protoflow) [:book:](https://docs.rs/protoflow) |
| [RAMEN 🍜](https://github.com/Zubax/ramen) | Lightweight actor-based message exchange library for embedded C++. | [@Zubax](https://github.com/Zubax) | C++ | MIT | 2025 | [:octocat:](https://github.com/Zubax/ramen) |
| [SciPipe](https://github.com/scipipe/scipipe) | Mature scientific workflow library for Go. | [@samuell](https://github.com/samuell) | Go | MIT | 2024 | [:octocat:](https://github.com/scipipe/scipipe) [:house:](https://scipipe.org) |

## Reference

### Concepts

This is a cross-reference for the widely varying nomenclature used in various
FBP implementations. "Classical FBP" here means [@jpaulm](https://github.com/jpaulm)'s
nomenclature as found in his pioneering [book] and his open-source implementations
(e.g., GoFBP, JavaFBP) that seeded the field.

| [Classical FBP]         | [Flux Theory] | [Apache NiFi]   | [NoFlo]    | [Node-RED]    | [RAMEN]         |
| :---------------------- | :------------ | :-------------- | :--------- | :------------ | :-------------- |
| Network                 | System        | Flow            | Graph      | Flow          | Network         |
| Subnet [^1]             | Subsystem     | Process Group   | Subgraph   | Subflow       | -               |
| Component [^2]          | Block         | Processor       | Component  | Node          | Actor           |
| Process [^3]            | Process       | Processor       | Process    | Node          | Actor           |
| Connection [^4]         | Connection    | Connection      | Connection | Wire          | Topic           |
| Port                    | Port          | Relationship    | Port       | Port          | Event/Behavior  |
| Information Packet (IP) | Message       | Flow File       | IP         | Message       | Message         |
| Initial Information Packet (IIP) | Property      | -      | IIP        | Config Node   | -               |
| Scheduler               | Scheduler     | Flow Controller | Runtime    | Runtime       | -               |

[^1]: Subnets were also known as "composite components" in classical FBP.
[^2]: Components were described as "black boxes" in classical FBP.
[^3]: Processes were interchangeably called "threads" in classical FBP.
[^4]: Connections were also known as "bounded buffers" in classical FBP.

### Languages

A growing number of programming languages implement concurrency primitives
suitable for building flow-based systems. Here follows a comparison of several
widely-used languages:

<table>
  <thead>
    <tr>
      <th></th>
      <th>Clojure</th>
      <th>Dart</th>
      <th>Erlang</th>
      <th>Golang</th>
      <th>Python</th>
      <th>Ruby</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Feature</td>
      <td>
        <a href="https://clojure.github.io/core.async/flow.html">core.async.flow</a>
      </td>
      <td>
        <a href="https://dart.dev/language/isolates">isolates</a>
      </td>
      <td>
        <a href="https://erlang.org/doc/system/ref_man_processes.html">processes</a>
      </td>
      <td>
        <a href="https://go.dev/tour/concurrency/1">goroutines</a>, <a href="https://go.dev/tour/concurrency/2">channels</a>
      </td>
      <td>
        <a href="https://docs.python.org/3/howto/a-conceptual-overview-of-asyncio.html">asyncio</a>
      </td>
      <td>
        <a href="https://docs.ruby-lang.org/en/master/language/ractor_md.html">ractors</a>
      </td>
    </tr>
    <tr>
      <td>Since</td>
      <td>
        <a href="https://clojure.org/news/2025/04/28/async_flow">2025</a>
      </td>
      <td>
        <a href="https://en.wikipedia.org/wiki/Dart_(programming_language)">1.0</a>
      </td>
      <td>
        <a href="https://en.wikipedia.org/wiki/Erlang_(programming_language)">OTP</a>
      </td>
      <td>
        <a href="https://go.dev/blog/go1">1.0</a>
      </td>
      <td>
        <a href="https://peps.python.org/pep-3156/">3.5</a>
      </td>
      <td>
        <a href="https://ruby-lang.org/en/news/2025/12/25/ruby-4-0-0-released/">4.0</a>
      </td>
    </tr>
    <tr>
      <td>Runtime</td>
      <td>
        <a href="https://clojure.github.io/core.async/clojure.core.async.flow.html"><code>core.async.flow</code></a>
      </td>
      <td>
        <a href="https://api.flutter.dev/flutter/dart-isolate/"><code>dart:isolate</code></a>
      </td>
      <td>
        <a href="https://erlang.org/doc/system/ref_man_processes.html"><code>spawn</code></a>
      </td>
      <td>
        <a href="https://go.dev/ref/spec#Go_statements"><code>go</code></a>, <a href="https://go.dev/ref/spec#Making_slices_maps_and_channels"><code>make(chan)</code></a>
      </td>
      <td>
        <a href="https://docs.python.org/3/library/asyncio.html"><code>asyncio</code></a>
      </td>
      <td>
        <a href="https://docs.ruby-lang.org/en/master/Ractor.html"><code>Ractor</code></a>
      </td>
    </tr>
    <tr>
      <td>Process</td>
      <td>
        <a href="https://clojure.github.io/core.async/clojure.core.async.flow.html#var-process"><code>(process)</code></a>
      </td>
      <td>
        <a href="https://api.flutter.dev/flutter/dart-isolate/Isolate-class.html"><code>Isolate</code></a>
      </td>
      <td>
        <a href="https://erlang.org/doc/system/ref_man_processes.html">process</a>
      </td>
      <td>
        <a href="https://go.dev/ref/spec#Go_statements">goroutine</a>
      </td>
      <td>
        <a href="https://peps.python.org/pep-0492/#specification">coroutine</a>
      </td>
      <td>
        <a href="https://docs.ruby-lang.org/en/master/Ractor.html"><code>Ractor</code></a>
      </td>
    </tr>
    <tr>
      <td>Port</td>
      <td>
        <a href="https://clojure.github.io/core.async/clojure.core.async.html#var-chan"><code>(chan)</code></a>
      </td>
      <td>
        <a href="https://api.flutter.dev/flutter/dart-isolate/ReceivePort-class.html"><code>ReceivePort</code></a>, <a href="https://api.flutter.dev/flutter/dart-isolate/SendPort-class.html"><code>SendPort</code></a>
      </td>
      <td>
        <a href="https://erlang.org/doc/system/ref_man_processes#message-queue-order">message queue</a>
      </td>
      <td>
        <a href="https://go.dev/ref/spec#Making_slices_maps_and_channels"><code>chan</code></a>
      </td>
      <td>
        <a href="https://docs.python.org/3/library/asyncio-queue.html"><code>asyncio.Queue</code></a>
      </td>
      <td>
        <a href="https://docs.ruby-lang.org/en/master/Ractor/Port.html"><code>Ractor::Port</code></a>
      </td>
    </tr>
    <tr>
      <td>Message</td>
      <td>
        <a href="https://clojuredocs.org/clojure.core/some_q"><code>some?</code></a>
      </td>
      <td>
        <a href="https://api.flutter.dev/flutter/dart-isolate/SendPort/send.html"><code>Object?</code></a>
      </td>
      <td>
        <a href="https://erlang.org/doc/apps/erts/erlang.html#t:any/0"><code>any()</code></a>
      </td>
      <td>
        <a href="https://go.dev/ref/spec#Basic_interfaces"><code>any</code></a>
      </td>
      <td>
        <a href="https://docs.python.org/3/library/stdtypes.html"><code>object</code></a>
      </td>
      <td>
        <a href="https://docs.ruby-lang.org/en/master/language/ractor_md.html#limited-sharing-between-ractors"><code>Object</code></a>*
      </td>
    </tr>
    <tr>
      <td>Parallelism</td>
      <td>
        <a href="https://clojure.github.io/core.async/flow-guide.html">thread-per-process</a>
      </td>
      <td>
        <a href="https://dart.dev/language/concurrency#how-isolates-work">multi-core</a>
      </td>
      <td>
        <a href="https://www.erlang.org/doc/system/ref_man_processes.html#process-creation">multi-core</a>
      </td>
      <td>
        <a href="https://go.dev/doc/faq#goroutines">multi-core</a>
      </td>
      <td>
        <a href="https://docs.python.org/3/library/asyncio-eventloop.html">single-threaded</a>†
      </td>
      <td>
        <a href="https://docs.ruby-lang.org/en/master/Ractor.html">multi-core</a>
      </td>
    </tr>
    <tr>
      <td>Scheduling</td>
      <td>
        <a href="https://clojure.github.io/core.async/clojure.core.async.flow.html#var-process">OS / JVM</a>
      </td>
      <td>
        <a href="https://dart.dev/language/concurrency#event-loop">cooperative</a>
      </td>
      <td>
        <a href="https://hamidreza-s.github.io/erlang/scheduling/real-time/preemptive/migration/2016/02/09/erlang-scheduler-details.html">preemptive</a>
      </td>
      <td>
        <a href="https://go.dev/src/runtime/preempt.go">preemptive</a>‡
      </td>
      <td>
        <a href="https://docs.python.org/3/library/asyncio-dev.html#concurrency-and-multithreading">cooperative</a>
      </td>
      <td>
        <a href="https://docs.ruby-lang.org/en/master/Ractor.html#class-ractor-ractors-vs-threads">OS threads</a>
      </td>
    </tr>
    <tr>
      <td>Isolation</td>
      <td>
        <a href="https://clojure.github.io/core.async/flow-guide.html">shared (immutable)</a>
      </td>
      <td>
        <a href="https://dart.dev/language/concurrency#how-isolates-work">fully isolated</a>
      </td>
      <td>
        <a href="https://www.erlang.org/doc/system/ref_man_processes.html#signals">fully isolated</a>
      </td>
      <td>
        <a href="https://go.dev/doc/faq#goroutines">shared memory</a>
      </td>
      <td>
        <a href="https://docs.python.org/3/library/asyncio.html">shared memory</a>
      </td>
      <td>
        <a href="https://docs.ruby-lang.org/en/master/language/ractor_md.html#limited-sharing-between-ractors">shared (limited)</a>
      </td>
    </tr>
    <tr>
      <td>Backpressure</td>
      <td>
        <a href="https://clojure.github.io/core.async/clojure.core.async.html#var-chan">bounded</a>
      </td>
      <td>
        <a href="https://api.flutter.dev/flutter/dart-isolate/ReceivePort-class.html">unbounded</a>
      </td>
      <td>
        <a href="https://www.erlang.org/doc/system/ref_man_processes.html#signals">unbounded</a>
      </td>
      <td>
        <a href="https://go.dev/ref/spec#Making_slices_maps_and_channels">configurable</a>
      </td>
      <td>
        <a href="https://docs.python.org/3/library/asyncio-queue.html#asyncio.Queue">configurable</a>
      </td>
      <td>
        <a href="https://docs.ruby-lang.org/en/master/Ractor/Port.html">unbounded</a>
      </td>
    </tr>
    <tr>
      <td>Supervision</td>
      <td>
        <a href="https://clojure.github.io/core.async/clojure.core.async.flow.html"><code>:error-chan</code></a>
      </td>
      <td>
        <a href="https://api.flutter.dev/flutter/dart-isolate/Isolate/addErrorListener.html"><code>addErrorListener</code></a>
      </td>
      <td>
        <a href="https://www.erlang.org/doc/apps/stdlib/supervisor.html">OTP supervisors</a>
      </td>
      <td>
        <a href="https://go.dev/ref/spec#Handling_panics"><code>recover</code></a>
      </td>
      <td>
        <a href="https://docs.python.org/3/library/asyncio-task.html#asyncio.Task">task exceptions</a>
      </td>
      <td>
        <a href="https://docs.ruby-lang.org/en/master/Ractor.html#method-i-join"><code>Ractor#join</code></a>
      </td>
    </tr>
  </tbody>
</table>

**Parallelism** describes whether the runtime can execute multiple processes
simultaneously on separate CPU cores. Erlang, Dart, Go, and Ruby all achieve
true multi-core parallelism. Clojure's `core.async.flow` runs each process on a
JVM thread (from configurable thread pools), also achieving multi-core
parallelism. Python's `asyncio` multiplexes coroutines on a single thread, so
it's concurrent but not parallel without reaching for `multiprocessing`.

**Scheduling** matters because it determines whether a long-running computation
can starve other processes. Erlang is the gold standard here with
reduction-counting preemption that guarantees fairness even for CPU-bound work.
Go adopted signal-based preemption in 1.14 to prevent tight loops from hogging a
core. Dart and Python are cooperative--a compute-bound isolate or coroutine must
explicitly yield. Clojure and Ruby delegate to the OS/JVM thread scheduler.

**Isolation** has direct implications for data safety in FBP networks. Erlang
and Dart processes have fully separate heaps and can only communicate by
copying messages. Go and Python have shared memory, requiring discipline to
avoid races. Clojure takes a middle path by encouraging immutable shared data.
Ruby's ractors restrict sharing to frozen/shareable objects.

**Backpressure** determines whether a fast producer can overwhelm a slow
consumer. Clojure's and Go's channels and Python's asyncio queues support
bounded buffers that block senders when full--a natural fit for FBP. Erlang,
Dart, and Ruby all have unbounded mailboxes/ports, meaning backpressure must be
implemented at the application level.

**Supervision** captures how errors in one process are detected and handled by
the network. Erlang's OTP supervisor trees are the most mature model. Clojure's
`core.async.flow` centralizes errors onto a dedicated `:error-chan`. The others
offer varying levels of support through error listeners, panic recovery, or
exception propagation from tasks.

## Community

Here follows a small sample of the fine folks developing FBP frameworks and/or
producing useful content about this approach to programming:

[@antonmi](https://github.com/antonmi),
[@apiri](https://github.com/apiri),
[@artob](https://github.com/artob),
[@bergie](https://github.com/bergie),
[@exceptionfactory](https://github.com/exceptionfactory),
[@goodlux](https://github.com/goodlux),
[@jm9e](https://github.com/jm9e),
[@joewitt](https://github.com/joewitt),
[@jpaulm](https://github.com/jpaulm),
[@knolleary](https://github.com/knolleary),
[@markap14](https://github.com/markap14),
[@mcgilman](https://github.com/mcgilman),
[@pavel-kirienko](https://github.com/pavel-kirienko),
[@ryrobes](https://github.com/ryrobes),
[@samuell](https://github.com/samuell),
[@statusfailed](https://github.com/statusfailed),
[@trustmaster](https://github.com/trustmaster),
[@tyoung3](https://github.com/tyoung3)

👉 [Join](https://join.slack.com/t/fbphq/shared_invite/enQtOTM4ODkzMTYyODE3LTJiMmNlZjhiMWY1MDY1ODA4Y2YzNDBlNDZlMTBkMDNlMjcwNzg2MGZhZjA2NjJjYTliYTM0OTIyYmM0Yzk0MDQ)
the [FBP Slack](https://fbphq.slack.com)! (Historically, there was also an active
[Flow Based Programming](https://groups.google.com/g/flow-based-programming)
Google group but these days it's unmaintained and has been overrun by spam.
Still, lots of useful information in the archives over there.)

## Credits

Kudos to [@samuell](https://github.com/samuell) for putting together the first
Awesome FBP list over at [samuell/awesome-fbp](https://github.com/samuell/awesome-fbp).

---

[![Share on X](https://img.shields.io/badge/share%20on-x-03A9F4?logo=x)](https://x.com/intent/post?url=https://github.com/flux-doctrine/awesome-fbp&text=Awesome%20Flow-Based%20Programming%20%28FBP%29)
[![Share on Reddit](https://img.shields.io/badge/share%20on-reddit-red?logo=reddit)](https://reddit.com/submit?url=https://github.com/flux-doctrine/awesome-fbp&title=Awesome%20Flow-Based%20Programming%20%28FBP%29)
[![Share on Hacker News](https://img.shields.io/badge/share%20on-hn-orange?logo=ycombinator)](https://news.ycombinator.com/submitlink?u=https://github.com/flux-doctrine/awesome-fbp&t=Awesome%20Flow-Based%20Programming%20%28FBP%29)
[![Share on Facebook](https://img.shields.io/badge/share%20on-fb-1976D2?logo=facebook)](https://www.facebook.com/sharer/sharer.php?u=https://github.com/flux-doctrine/awesome-fbp)
[![Share on LinkedIn](https://img.shields.io/badge/share%20on-linkedin-3949AB?logo=linkedin)](https://www.linkedin.com/sharing/share-offsite/?url=https://github.com/flux-doctrine/awesome-fbp)

[Classical FBP]: https://jpaulm.github.io/fbp/
[Apache NiFi]: https://nifi.apache.org/docs/nifi-docs/html/user-guide.html#terminology
[Async-Flow]: https://github.com/artob/async-flow#glossary
[Flux Theory]: https://github.com/flux-doctrine/flux-theory
[NoFlo]: https://noflojs.org/documentation/glossary/
[Node-RED]: https://nodered.org/docs/user-guide/concepts
[RAMEN]: https://github.com/Zubax/ramen
[book]: https://www.amazon.com/dp/B004PLO66O
