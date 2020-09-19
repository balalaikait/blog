## balalaika IT newsletter #10

*If you like this newsletter subscribe to our new issues at http://balalaikait.com/*

# General

- Back to basics. Do you remember how NAT traversal works? David Anderson wrote a [lengthy post](https://tailscale.com/blog/how-nat-traversal-works/) with great visuals to remind you.
- Steve Yegge [explains](https://medium.com/@steve.yegge/dear-google-cloud-your-deprecation-policy-is-killing-you-ee7525dc05dc) why vendor locks mixed with poor backward compatibility could make anyone question the benefits of a cloud. 
- CockroachDB team recently introduced Pebble, an open-source K/V store inspired by RocksDB. Read this [blog post](https://www.cockroachlabs.com/blog/pebble-rocksdb-kv-store/) to learn why they decided to do write it.
- Here is a great [series](https://idndx.com/2014/09/01/the-implementation-of-epoll-1/) of blog posts on implementation of Linux `epoll` for those of you who enjoy learning about kernel.
- If you're not familiar with Log-structured merge-tree data structure (aka LSM tree), but want to learn it, Tarantool DB team did a great job on documenting their [implementation](https://www.tarantool.io/en/doc/2.2/book/box/engines/#storing-data-with-vinyl).

# Java

- Java 15 is [GA](https://mail.openjdk.java.net/pipermail/announce/2020-September/000291.html). It brings internal JVM changes (say, it disables biased locking), stable releases of low-latency garbage collectors (ZGC and Shenandoah), experimental APIs (such as Foreign-Memory Access API), and some more goodies.
- JNI has a fame of being "slow". But where the JNI overhead comes from and how critical it is? If you want to hear an explanation with all low-level details, here is a great [talk](https://youtu.be/LoyBTqkSkZk) by Cliff Click.

# JavaScript

- Moment.js team now considers the library to be a legacy project in maintenance mode.  It is not dead, but it is indeed done. Read more about the reasoning [here](https://momentjs.com/docs/#/-project-status/).

# React

- Animations can make a site stand out. Or, they can just as easily kill the experience. Prasanjit Singh presents us with [the ground rules](https://css-tricks.com/ground-rules-for-web-animations/) to master web animations.
- AVIF is a fairly new kid on the block and it promises us a new future of the leaner web with smaller images. JPEG is not dead yet, but we keep our fingers crossed. Here is a [concise read](https://jakearchibald.com/2020/avif-has-landed/) from Jake Archibald on the new image format.
- Wondering how Facebook's Recoil works? Bennett Hardwick [explained it for you](hhttps://bennetthardwick.com/blog/recoil-js-clone-from-scratch-in-100-lines/) in 100 lines of code. 