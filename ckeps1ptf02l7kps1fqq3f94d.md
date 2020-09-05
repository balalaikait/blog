## balalaika IT newsletter #4

# Frontend
- [An in-depth guide on building your own 100% reactive renderer from scratch](https://indepth.dev/solidjs-reactivity-to-rendering/).
- [A must-read research on CPU cost of JavaScript](https://calendar.perfplanet.com/2019/javascript-component-level-cpu-costs/).
- [Bootstrap 5 alpha is out!](https://blog.getbootstrap.com/2020/06/16/bootstrap-5-alpha/) This time no jQuery and no IE11.
- [A guided tour](https://www.youtube.com/playlist?list=PLo3w8EB99pqJVPhmYbYdInBvAGarDavh-) of what it is like to work on the SpiderMonkey (JavaScript engine) compiler and improve conformance with ECMA-262, the JavaScript Specification. From Mozilla to people with love.

# Node.js
- Sad to say it, but it looks like [hapi.js project is reaching its end](https://twitter.com/hapijs/status/1275887984114413569?s=19). If you happen to use hapi.js, you should consider switching to another web framework in the nearest future.
- As of v7 npm support both yarn.lock and package-lock.json. [Here is a great read](https://blog.npmjs.org/post/621733939456933888/npm-v7-series-why-keep-package-lockjson) on npm v7 treats them and about the future of npm dependency resolution algorithms.

# Java
- HotSpot JVM has tons of optimizations all over the place. For instance, even the default hashCode() hides some secrets. Learn more about this optimization [here](https://srvaroa.github.io/jvm/java/openjdk/biased-locking/2017/01/30/hashCode.html).
- As an interesting follow-up, you might want to take a look at the j.l.String#hashCode() implementation which caches the hash code in a non-volatile `hash` field. This optimization was described in the Java Concurrency in Practice book [here](http://hg.openjdk.java.net/jdk8/jdk8/jdk/file/687fd7c7986d/src/share/classes/java/lang/String.java#l117) and [here](http://hg.openjdk.java.net/jdk8/jdk8/jdk/file/687fd7c7986d/src/share/classes/java/lang/String.java#l1452). Do not do it at home!
- If you are not familiar with the history behind Generics, which have a controversial reputation in Java community, you should read [this post](http://cr.openjdk.java.net/~briangoetz/valhalla/erasure.html) from Brian Goetz.

# General
- Jepsen team recently did [an analysis of RedisRaft](https://jepsen.io/analyses/redis-raft-1b3fbf6), a new module that provides strict serializability for Redis. As usual, some issues were found. As usual, some promises of fixes were made. 