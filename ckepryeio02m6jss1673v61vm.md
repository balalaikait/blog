## balalaika IT newsletter #2

# Frontend
- Mark Erikson (Redux maintaiiner) provides us with ["details on how React rendering behaves, and how use of Context and React-Redux affect rendering"](https://blog.isquaredsoftware.com/2020/05/blogged-answers-a-mostly-complete-guide-to-react-rendering-behavior/). Must-read for every React dev!
- Facebook has finally released [its own state management library](https://recoiljs.org/). It's still experimental, but it's definitely worth a try. Given that it comes from the same company, it's reasonable to expect that it plays nice with the upcoming concurrent mode, suspense, and anything else we don't know of yet.
- [A great read from Harry Roberts](https://csswizardry.com/2020/05/the-fastest-google-fonts/) on how to make your font render faster than ever.

# Node.js
- In our view, it's the most comprehensive yet not bloated [guide on how the event loop works](https://blog.insiderattack.net/event-loop-and-the-big-picture-nodejs-event-loop-part-1-1cb67a182810). An absolute must-read for every Node.js developer!
- Have you ever wondered how V8 manages its memory? [Here is a concise overview with great visuals](https://deepu.tech/memory-management-in-v8/). 

# General
- A long-read coming in 9 parts on [what every programmer should know about the memory](https://lwn.net/Articles/250967/). It is 13 years old, but it is as relevant today as it was back then.
- Async context propagation is a pain in the ass in any eco-system. Google provided us with an [outstanding comparison of how different languages and frameworks approach it](https://docs.google.com/document/d/1tlQ0R6wQFGqCS5KeIw0ddoLbaSYx6aU7vyXOkv-wvlM/edit?usp=sharing).
- [A new episode of a never-ending battle between Kyle Kingsbury (author of a well-known Jepsen)  and MongoDB](http://jepsen.io/analyses/mongodb-4.2.6). He evaluated MongoDB version 4.2.6, and found that even at the strongest levels of read and write concern, it failed to preserve snapshot isolation. MongoDB promises a patch in 4.2.8.
- Everybody knows B-trees, right? But what about other ways to speed up your search? [Marko Kevac from Badoo speaks about their usage of bitmap indexes](https://youtu.be/WvlUH6MjUuI).

# Bonus
- Did you know that it's simple enough to build a time series storage on top of RocksDB which is capable of writing 400K data points/sec on decent HW? And yes, it uses bitmaps. Andrey P, who is a big fan of time series (and bitmaps), recently [did a talk on the topic](https://youtu.be/1fzae--iHYU).