## balalaika IT newsletter #12

**This is our 12th newsletter. It means we are exploring the world of web development together for half a year. Said to say, but there will not be any new issues of the newsletter for a long while. This is not a goodbye, rather a see you later. In the meantime, feel free to subscribe to the personal blogs of our curators: https://medium.com/@apechkurov and https://blog.goncharov.page/. Let's stay in touch!**

# General
- [In this post](http://brandonharris.io/redshift-clickhouse-time-series/) Brandon Harris shows us how to synthesize billions of rows of true time series data with an autoregressive component, and then explore it with ClickHouse, a big data scale OLAP RDBMS, all on AWS.
- [DuckDB](https://duckdb.org/) - an embeddable database for analytical workloads. 
- Do you think mmap is faster than syscalls? Well, mmap could make your app run faster, but with strings attached. Sasha Fedorova gives us a [great in-depth explanation of how it works](https://medium.com/@sasha_f/why-mmap-is-faster-than-system-calls-24718e75ab37).
- Distributed transactions are hard to implement right. In fact, many modern databases do not even bother with supporting them. FaunaDB is not one of those, as it builds transactions on top of [Calvin](https://blog.acolyer.org/2019/03/29/calvin-fast-distributed-transactions-for-partitioned-database-systems/) algorithm.

# Java
- Tiered JIT compilation can be found in multiple modern runtimes and JVM is no difference. Some time ago Rafael Winterhalter gave a nice [talk](https://youtu.be/hjpzLXoUu1Y) on basic principles behind C2 compiler in HotSpot.
- `ForkJoinPool` is available since Java 7 and used in several places within standard library, like parallel streams. It embeds many good ideas, like queue per worker and work stealing. If you are not familiar with these details, you may find them in the original [paper](http://gee.cs.oswego.edu/dl/papers/fj.pdf) by Doug Lea.

# JavaScript
- Monomorphism is a very important definition for JIT compilation in JavaScript (and not only - see the above Rafael Winterhalter's talk). Several years ago, Vyacheslav Egorov wrote a brilliant [post](https://mrale.ph/blog/2015/01/11/whats-up-with-monomorphism.html) to explain how V8's JIT compiler makes use of monomorphism.
- [esbuild](https://github.com/evanw/esbuild) - a new kid in the family of bundlers and minifiers. Written in Go. Claims to be extremely fast.
- NPM 7 is out. Lots of new goodies. Read more about them [here](https://dev.to/ruyadorno/announcing-npm7-16j0). 