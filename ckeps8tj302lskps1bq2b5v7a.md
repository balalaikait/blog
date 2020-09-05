## balalaika IT newsletter #9

*If you like this newsletter subscribe to our new issues at http://balalaikait.com/*

# General
- CPU caching 101 from Nick Evanson. A [concise read](https://www.techspot.com/article/2066-cpu-l1-l2-l3-cache/) about the fundamentals to get you started on how it works and why we need it. 
- Over the last two years, Uber has attempted to reduce microservice complexity while still maintaining the benefits of a microservice architecture. With [this blog post]( https://eng.uber.com/microservice-architecture/) we hope to introduce our generalized approach to microservice architectures, which we refer to as “Domain-Oriented Microservice Architecture” (DOMA).
- Distributed locks are infamous for being hard to use right. Some time ago Hazelcast team introduced locks as a part of CP Subsystem based on Raft, a well-known consensus algorithm. This [blog post](https://hazelcast.com/blog/long-live-distributed-locks/) describes potential pitfalls of distributed lock and how FencedLock solves them.
- Great engineers of the past have a lot to learn from. In [this talk](https://youtu.be/bo5WL5IQAd0) explains how Erlang was designed to scale well on multicore machines.

# JavaScript
- ES6 introduced many nice built-in collections, such as Map, Set, WeakMap, and WeakSet. Unfortunately, the spec does not put many requirements for concrete implementations. If you want to learn practical details of Maps and Sets implementation in V8, read this [blog post](https://itnext.io/v8-deep-dives-understanding-map-internals-45eb94a183df) by Andrey P.
- JIT compiler is what makes V8 and other JS engines blazing fast. But exactly does it do? Watch this [talk](https://youtu.be/p-iiEDtpy6I) by Franziska Hinkelmann to learn the answer.

# React
- Is it possible to build SPAs purely in Rust and without writing a single line of JavaScript? The short answer is YES! Read about the experiment [here](http://www.sheshbabu.com/posts/rust-wasm-yew-single-page-application/).

# Node.js
- A [concise guide](https://httptoolkit.tech/blog/how-to-debug-node-segfaults) on how to debug segmentation faults in Node.js.

# Java
- Did you know that `java.security.SecureRandom` may be more or less secure depending on the configuration? This [blog post](https://tersesystems.com/blog/2015/12/17/the-right-way-to-use-securerandom/) explains how to use it in the right way.