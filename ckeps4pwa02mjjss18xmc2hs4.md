## balalaika IT newsletter #6

# Frontend
- A [comprehensive guide](https://jkettmann.com/beginners-guide-to-testing-react/) on testing in React from Johannes Kettmann. A single long-read that covers it all.
- Did you ever hear of CSS Houdini? Lisi Linhart did not just hear about it, but went above and beyond and wrote a [great piece](https://lisilinhart.info/posts/css-houdini-performance) on its performance. 
- Adobe open-sourced its own [design system and state management library](https://react-spectrum.adobe.com/blog/introducing-react-spectrum.html) for React!

# Node.js
- Moment.js, Luxon or date-fns? Hopefully, one day there will be a built-in API that if not removes but at least reduces the need for third-party libraries to manipulate date and time. Here is a [TC39 proposal for the new Temporal API](https://tc39.es/proposal-temporal/docs/index.html) that is destined to fix JS Date.
- Nowadays almost every Node.js developer has a good understanding of the event loop principles. Yet, only some folks understand how node works from the low-level perspective. If you want to learn more about non-blocking I/O, watch this interesting [talk](https://youtu.be/P9csgxBgaZ8) by Sam Roberts.

# Java
- Some of `java.util.concurrent.atomic` classes expose `#lazySet()` methods which may be a significant performance win for a single writer scenario in the concurrent mode. If you are not familiar with those methods and want to understand how they differ from ordinary `volatile` writes take a look at this [post](http://psy-lob-saw.blogspot.com/2012/12/atomiclazyset-is-performance-win-for.html) and [this](http://psy-lob-saw.blogspot.com/2016/12/what-is-lazyset-putordered.html) one as well.
- Everyone knows Netty, which is used as a building block in many other frameworks. One of the main reasons behind that popularity is performance. Watch [this talk](https://youtu.be/hvYqSz_BgUM) to learn about some optimizations inside Netty, including the "do not try this at home" ones.

# General
- Linux kernel scheduler has to make a lot of decisions and it has to make them fast. Here is a [detailed explanation](https://helix979.github.io/jkoo/post/os-scheduler/) of how the scheduler works.
- Writing correct concurrent code is hard, no doubts. Writing performant concurrent code is even harder. If you aim for both of these goals, read this awesome [blog post](https://travisdowns.github.io/blog/2020/07/06/concurrency-costs.html) that compares the costs of different concurrent primitives.