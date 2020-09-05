## balalaika IT newsletter #7

# Frontend
- [A short, yet insightful post](https://engineering.fb.com/web/facebook-com-accessibility/) about enhanced A11Y at Facebook. You might think it is easy and not a big deal until you have to re-write your whole application to meet the [AIRA guidelines](https://www.w3.org/TR/wai-aria-practices-1.2/).

# Node.js
- What do you know about the speculative compilation in JavaScript? [This lengthy read](https://webkit.org/blog/10308/speculation-in-javascriptcore/) goes in-depth of how modern JS VMs make your code run faster.
- There is a certain learning curve related with contributions to the native side of Node.js core. Luckily this great [tips and tricks post](https://joyeecheung.github.io/blog/2018/12/31/tips-and-tricks-node-core/) from Joyee Cheung is there to help you.

# Java
- It is not a big secret that GC may introduce latency spikes. Such spikes are especially harmful in case of stream processing engine, like Hazelcast Jet or Apache Spark Streaming. Read [this blog post series](https://jet-start.sh/blog/2020/06/09/jdk-gc-benchmarks-part1) from Jet team to see results of various experiments with modern Java garbage collectors.
- Did you know that there is a Java Engineering Group in Microsoft? Moreover, these guys wrote a [nice JEP](https://github.com/microsoft/openjdk-proposals/blob/master/stack_allocation/Stack_Allocation_JEP.md) on Stack Allocation support in HotSpot C2 to eliminate non-escaping heap allocations where applicable.

# General
- Distributed systems are much more than the AP/CP choice implied by the so called CAP theorem. Conflict-free replicated data types (CRDT) assume eventual consistency, scale really well, and provide math-based way to resolve inconsistencies between replicas. In [this talk](https://youtu.be/x7drE24geUw) Martin Kleppmann goes beyond the introductory material on CRDTs.
- API seems to be so natural term that we assume it was there since the beginning of computer era. But that is not true. If you want to learn when and how the concept of API was invented, watch [this talk](https://youtu.be/LzMp6uQbmns) from Joshua Bloch.
- Dropbox migrated from Nginx to Envoy. [In this blogpost](https://dropbox.tech/infrastructure/how-we-migrated-dropbox-from-nginx-to-envoy) Alexey Ivanov  and Oleg Guba talk about the old Nginx-based traffic infrastructure, its pain points, and the benefits we gained by migrating to Envoy.