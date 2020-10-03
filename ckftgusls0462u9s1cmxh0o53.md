## balalaika IT newsletter #11

*If you like this newsletter subscribe to our new issues at https://balalaikait.com/*

# General
- Joseph Gentle [tells us](https://josephg.com/blog/crdts-are-the-future/) about the rise of CRDTs and why he thinks in could beat Operational Transform in many aspects.
- One who wants to write fast code has to understand weak and strong points of modern HW. Cliff Click gave a brilliant [talk](https://youtu.be/OFgxAFdxYAQ) where he explains those points.
- Thread-Per-Core (TPC) is a valid approach for building high-performance server-side software. Yet, it is not trivial to build it right and has a lot of quirks. Some time ago, Redpanda team managed to use TCP architecture on top of Seastar framework and [shared](https://vectorized.io/tpc-buffers/) their experience.

# Java
- James Gosling recently gave a lengthy [interview](https://youtu.be/IT__Nrr3PNI) on Java, JVM, Emacs, and the early days of software engineering.
- Kotlin gets more and more popular among the JVM community. In this [post](https://blog.jetbrains.com/kotlin/2020/09/the-dark-secrets-of-fast-compilation-for-kotlin/) Andrey Breslav sheds some light on the secrets of fast compilation in Kotlin.

# JavaScript
- Atomics module, which holds low-level synchronization primitives useful for Web Workers, keeps getting new features, like `Atomics.waitAsync` method, which is currently at TC39's stage 3. V8 team wrote this [blog post](https://v8.dev/features/atomics) to explain how Atomics can be used to write sync and async lock primitives.
- A great reminder that even high-level languages like JavaScript still suffer from memory leaks. [This time](https://web.dev/detached-window-memory-leaks/) the case is kind of unusual  - detached windows. Be a good engineer and clean up after yourself!

# React
- Kent C. Dodds [tells us](https://epicreact.dev/myths-about-useeffect/) about common pitfalls and myths related to `useEffect`.
