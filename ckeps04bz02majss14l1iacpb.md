## balalaika IT newsletter #3

# Frontend
- TJ VanToll watched all 27 React Europe talks and provided [us with his notes](https://www.telerik.com/blogs/i-watched-all-27-react-europe-talks-so-you-dont-have-to). 
- [A good read from PayPal](https://medium.com/paypal-engineering/reusing-ui-components-at-enterprise-level-a7df1ea1f8dd) on how they approach sharing UI components at their enterprise level.
- [A Visual Guide To React Mental Models, Part 2.](https://obedparla.com/code/a-visual-guide-to-react-mental-models-part-2-use-state-use-effect-and-lifecycles/) This time it's useState, useEffect and lifecycles.

# Node.js
- [Pointer compression](https://v8.dev/blog/pointer-compression) is a low-level feature recently introduced in V8. Not only it saves memory, but it improves the performance (surprise!). Hopefully, it will be available in Node.js in the future.
- Did you know that there were experiments with jemalloc in Node.js core? As expected, not a silver bullet, but definitely [an interesting read](https://github.com/nodejs/node/issues/21973).

# Java
- [An in-depth overview (with benchmarks!)](https://jet-start.sh/blog/2020/06/09/jdk-gc-benchmarks-part1) of modern garbage collectors applied to a stream processing framework.
- While pointer compression is a recent improvement of V8, [Hotspot JVM had compressed oops for ages](https://wiki.openjdk.java.net/display/HotSpot/CompressedOops).

# General
- Your [ultimate guide](https://github.com/donnemartin/system-design-primer) on learning how to design large-scale systems and prep for the system design interview.
- Joshua Thijssen [describes ALL AWS services](https://adayinthelifeof.nl/2020/05/20/aws.html)  in one sentence each.
- Most modern server machines have NUMA memory architecture, so modern software has to be NUMA-friendly. If you are not familiar with NUMA yet, [check out this post](https://frankdenneman.nl/2016/07/07/numa-deep-dive-part-1-uma-numa/).