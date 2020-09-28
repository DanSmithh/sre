# 📚 Knowledge
> an attempt to centralize my studies/links/annotations for reference purposes

At the moment this is not useful for anyone but myself, if at some point I find it usefult I'll make it public.

<img src="resources/topic-graph.png" width="100%">
(click to see the large version)

## How to use this repo?

The README topics/links are organized following above chart. High-level subjects are usually parent topics, sub-topics are usually specialization of the main subject.

Depending on your level, you can dive deeper into a subject's sub-topics, or just move to the next one.

* Left to write: indicate how generic subjects are
* Top-bottom: Order of importance/relevancy and specialization of each subject or sub-category

e.g.:

Software Engineering
  * Databases
    * SQL
      * Postgres Basics
      * Postgres Internal
        * How postgres replication works
        * Parsing postgres WAL(WriteAheadLog)
  * Versioning

For instance, take into account the snaptshot above. If you already know how to use SQL Databases, you might want to either:

* Continue to the right, learning more more about Postgres, and to the bottom, its internals, specialized internals like replication and WAL.
* Continue to the bottom/next topic: `Programming Languages`.

### Tags
> Categories to the links

* 🌍 - Interesting Link
* 📰 - Article / Paper
* 📕 - Book
* 💻 - Project
* 🎓 - Online Course
* 📼 - Video Presentation / Content
* 🎥 - Slides Presentation
* ✍🏼 - Written/Made by me
* 📝 - My annotations
* 🆓 - Free / No money required
* 💰 - Paid
* 💪🏼 - Practice
* 🐦 - Person to Follow on Twitter
* ⭐️ - Favourite Option (when there are many alternatives)
* 👨🏻‍🔧- Workshop

## References

* Site Reliability Engineering
  * Culture
    * Introductory
      * [So you want to be an SRE? - Krishelle Hardson-Hurley](https://hackernoon.com/so-you-want-to-be-an-sre-34e832357a8c) 📰 🆓
    * Deeper Introduction
      * [Site Reliability Engineering - How Google Runs Production Systems](https://landing.google.com/sre/books/) 📕 🆓
      * [The Site Reliability Workbook - Practical Ways to Implement SRE](https://landing.google.com/sre/books/) 📕 🆓
      * [SRE - Keeping Google up and running 24/7](https://www.youtube.com/watch?v=yXI7r0_J29M) 📼 🆓
      * [Keys to SRE - Google](https://www.youtube.com/watch?v=n4Wf14e2jxQ) 📼 🆓
      * [Who/What? is SRE - Google (Panel)](https://www.youtube.com/watch?v=P83XESU3oZ8) 📼 🆓
      * Google Series on SRE - class SRE implements DevOps
        * [What's the Difference Between DevOps and SRE?](https://www.youtube.com/watch?v=uTEL8Ff1Zvk) 📼 🆓
        * [SLIs, SLOs, SLAs, oh my!](https://www.youtube.com/watch?v=tEylFyxbDLE) 📼 🆓
        * [Risk and Error Budgets](https://www.youtube.com/watch?v=y2ILKr8kCJU) 📼 🆓
        * [Toil and Toil Budgets](https://www.youtube.com/watch?v=IvQ-15-yE_c) 📼 🆓
        * [Now SRE Everyone Else with CRE!](https://www.youtube.com/watch?v=GQPzaq-owYM) 📼 🆓
        * [Managing Risks as a Site Reliability Engineer](https://www.youtube.com/watch?v=4kGu1_M7Igg) 📼 🆓
        * [Actionable Alerting for Site Reliability Engineers](https://www.youtube.com/watch?v=CGldVD5wR-g) 📼 🆓
        * [Observability of Distributed Systems](https://www.youtube.com/watch?v=SoZZzB-yTOk) 📼 🆓
        * [Incident Management](https://www.youtube.com/watch?v=n4y9dwinPBQ) 📼 🆓
        * [Postmortems and Retrospectives](https://www.youtube.com/watch?v=UBe7U2b3tsA) 📼 🆓
    * Use cases
      * [Site Reliability Engineering - Google - Christof Leng](https://www.youtube.com/watch?v=d2wn_E1jxn4&) 📼 🆓
      * [Implementing SLOs for a New Service - Squarespace](https://www.youtube.com/watch?v=ffbGyHPWwZM) 📼 🆓
      * [Shipping Software with an SRE Mindset - Circonous](https://www.youtube.com/watch?v=TZWWkvxFXls) 📼 🆓
      * [Latency SLOs Done Right - Circonous](https://www.youtube.com/watch?v=iPotMqzOsDI) 📼 🆓
      * [Site Reliability Engineering at Dropbox - Tammy Buttow](https://www.youtube.com/watch?v=ggizCjUCCqE) 📼 🆓
      * [190 Countries and 5 core SREs - Netflix - Jonah Horowitz](https://www.youtube.com/watch?v=koGaH4ffXaU) 📼 🆓
    * People to Follow
      * [Liz Fong-Jones](https://twitter.com/lizthegrey) 🐦
      * [Seth Vargo](https://twitter.com/sethvargo) 🐦
      * [Tammy Buttow](https://twitter.com/tammybutow)
    * Monitoring (See later Section)
    * Being on Call
    * Post-mortem
  * Software Engineering
    * Version Control
      * git
        * [Version Control with Git](https://learning.oreilly.com/library/view/version-control-with/9781449345037/) 📕 💰
    * Programming Languages
      * Paradigms
        * [Coursera - Programming Languages - Part A](https://www.coursera.org/learn/programming-languages) 📼 🎓 🆓
        * [Coursera - Programming Languages - Part B](https://www.coursera.org/learn/programming-languages-part-b) 📼 🎓 🆓
        * [Coursera - Programming Languages - Part C](https://www.coursera.org/learn/programming-languages-part-c) 📼 🎓 🆓
      * **Functional Programming Languages**
        * Haskell
          * General Overview
            * [Haskell From First Principles](http://haskellbook.com) 📕 💰
              * [Book Exercises](https://github.com/marceloboeira/hffp) 📝 💪🏼 🆓
            * [Simon Peyton Jones - Escape from the ivory tower - the Haskell journey](https://www.youtube.com/watch?v=re96UgMk6GQ) 📼 🆓
            * [Simon Peyton Jones - A History of Haskell - being lazy with class](https://www.youtube.com/watch?v=06x8Wf2r2Mc) 📼 🆓
            * [Andrew Rademacher - Demystifying Haskell](https://www.youtube.com/watch?v=apBWkBDVlow) 📼 🆓
          * Use cases
            * Facebook
              * [Bryan O'Sullivan - The Bright Side of High Level Languages](https://www.youtube.com/watch?v=kGa78HQv_LQ) 📼 🆓
              * [Jon Coens - The Road to Running Haskell at Facebook Scale](https://www.youtube.com/watch?v=sl2zo7tzrO8) 📼 🆓
          * Practice
            * [The Monad Challenges](http://mightybyte.github.io/monad-challenges/) 💪🏼 🆓
        * Concepts
          * Functional Programming
            * [Computerphile - Functional Programming & Haskell](https://www.youtube.com/watch?v=LnX3B9oaKzw) 📼 🆓
          * Lambda Calculus
            * [Computerphile - Lambda Calculus](https://www.youtube.com/watch?v=eis11j_iGMs) 📼 🆓
            * [Lambda Calculus - Fundamentals of Lambda Calculus & Functional Programming](https://www.youtube.com/watch?v=3VQ382QG-y4) 📼 🆓
            * [Lambda Calculis - Church Encodings && Combinators](https://www.youtube.com/watch?v=pAnLQ9jwN-E) 📼 🆓
            * The Y Combinator
              * [Computerphile - Y Combinator](https://www.youtube.com/watch?v=9T8A89jgeTI) 📼 🆓
          * Monads
            * [Computerphile - What is a Monad?](https://www.youtube.com/watch?v=t1e8gqXLbsU) 📼 🆓
            * [Functional Programming Patterns for Mere Mortals - Daniel Chambers](https://www.youtube.com/watch?v=v9QGWbGppis) 📼 🆓
      * **Systems Programming Languages**
        * Rust
          * [The Rust Programming Language](https://doc.rust-lang.org/stable/book/) 📕 🆓
            * [Annotations](https://github.com/marceloboeira/trpl) 📝
            * SubProjects
              * [grab](https://github.com/marceloboeira/grab) 👋🏼 like grep, but simpler [Chapters' 12/13 project].
              * [dull](https://github.com/marceloboeira/dull) 🤪 a dummy multi-thread HTTP server [Chapter's 20 project].
          * General Overview
            * [Aaron Turon - Rust: confident, productive systems programming](https://www.youtube.com/watch?v=C6dNx9pY7p8) 📼 🆓
            * [Steve Klabnik - The History of Rust](https://www.youtube.com/watch?v=79PSagCD_AY) 📼 🆓
          * Use cases
            * [Raph Levien - A Modern Editor Built in Rust](https://www.youtube.com/watch?v=SKtQgFBRUvQ) 📼 🆓
          * Testing Frameworks
            * [Speculate](https://github.com/utkarshkukreti/speculate.rs) Adds RSpec like behavior to rust via macros
          * [Programming Rust](https://learning.oreilly.com/library/view/programming-rust/9781491927274/) 📕 💰
        * Go
          * Concurrency
            * [Concurrency in Go](https://learning.oreilly.com/library/view/concurrency-in-go/9781491941294/) 📕 💰
          * Garbage Collector
            * [Golang's Realtime GC in Theory and Practice](https://www.youtube.com/watch?v=bMujSVMarqY) 📼 🆓
            * [Garbage Colletor Handbook](https://learning.oreilly.com/library/view/the-garbage-collection/9781315388007/) 📕 💰
    * Programming Topics
      * Algorithms and Data Structures
        * [Udacity - Intro to Data Structures and Algorithms by Google](https://eu.udacity.com/course/data-structures-and-algorithms-in-python--ud513) 🆓 🎓 📼
        * [Coursera - Algorithms - Part 1 - Elementary data structures, sorting, and searching algorithms](https://www.coursera.org/learn/algorithms-part1) 🆓 🎓 📼
        * [Coursera - Algorithms - Part 2 - Graph and string-processing algorithms](https://www.coursera.org/learn/algorithms-part2) 🆓 🎓 📼
        * [Courated List of the 10 best free resources](https://medium.freecodecamp.org/these-are-the-best-free-courses-to-learn-data-structures-and-algorithms-in-depth-4d52f0d6b35a) 📰 🆓
         * Alternative Data Structures
           * [“Esoteric Data Structures and Where to Find Them” - Allan Deutsch](https://www.youtube.com/watch?v=-8UZhDjgeZU) 📼 🆓
                * 0:36 Slot map
                * 10:08 Bloom filters (non-counting)
                * 16:46 Navigation meshes
                * 20:36 Hash pointer / Block chain / Merkle tree
           * Probabilistic Data Structures
             * Bloom Filter
               * [An Introduction to Bloom Filter (Probably Yes, Always No)](https://www.youtube.com/watch?v=x2sLjRK56YU) 📼 🆓
               * [Bloom Filters](https://www.youtube.com/watch?v=heEDL9usFgs) 📼 🆓
               * [Bloom filter for System Design applications](https://www.youtube.com/watch?v=Bay3X9PAX5k) 📼 🆓
               * [Bloom Filters](https://www.youtube.com/watch?v=bEmBh1HtYrw) 📼 🆓
             * Count-Min-Sketch
               * [Big Data with Sketchy Structures, Part 1 — the Count-Min Sketch](https://towardsdatascience.com/big-data-with-sketchy-structures-part-1-the-count-min-sketch-b73fb3a33e2a) 📰 🆓
               * [Count min sketch | Efficient algorithm for counting stream of data | system design components](https://www.youtube.com/watch?v=ibxXO-b14j4) 📼 🆓
    * Databases
      * Theory
        * [Designing Data-Intensive Applications - Martin Kleppmann](http://dataintensive.net) 📕 💰
        * [CAP Theorem Revisited](http://robertgreiner.com/2014/08/cap-theorem-revisited/) 📰 🆓
        * [The Pathologies of Big Data](https://queue.acm.org/detail.cfm?id=1563874) 📰 🆓
        * Scaling
        * Replication
          * --
        * Sharding
          * [Understanding Database Sharding - DigitalOcean](https://www.digitalocean.com/community/tutorials/understanding-database-sharding) 📰 🆓 ⭐️
          * [Sharding in Plain English - Citrus Data Blog](https://www.citusdata.com/blog/2018/01/10/sharding-in-plain-english/) 📰 🆓
          * [Introduction to Sharding - B's March (MongoDB Focused)](https://www.youtube.com/watch?v=4upppuW7lGE) 📼 🆓
          * [Sharding & Database Partitioning | System Design Basics](https://www.youtube.com/watch?v=RynPj8C0BXA) 📼 🆓
          * [System Design - Sharding | Data Partitioning](https://www.youtube.com/watch?v=yNrVexoEnFM) 📼 🆓
      * SQL
        * PostgreSQL
          * [Postgres: Up & Running](https://learning.oreilly.com/library/view/postgresql-up-and/9781491963401/) 📕 💰 ⭐️
          * [Learning PostgreSQL 11](https://learning.oreilly.com/library/view/learning-postgresql-11/9781789535464/) 📕 💰
          * [Mastering PostgreSQL 11 - Second Edition](https://learning.oreilly.com/library/view/mastering-postgresql-11/9781789537819/) 📕 💰
          * [Understanding Advanced Datatypes in PostgreSQL](https://www.youtube.com/watch?v=h0eEJ7uX13Q) 📼 🆓
          * [Updating a 50 terabyte PostgreSQL database](https://medium.com/adyen/updating-a-50-terabyte-postgresql-database-f64384b799e7) 📰 🆓
          * [How Twitch uses PostgreSQL](https://blog.twitch.tv/how-twitch-uses-postgresql-c34aa9e56f58) 📰 🆓
          * [Handling Growth with Postgres: 5 Tips From Instagram](https://instagram-engineering.com/handling-growth-with-postgres-5-tips-from-instagram-d5d7e7ffdfcb) 📰 🆓
          * [Updating a 50 terabyte PostgreSQL database](https://medium.com/adyen/updating-a-50-terabyte-postgresql-database-f64384b799e7) 📰 🆓
          * [Sharding & IDs at Instagram](https://instagram-engineering.com/sharding-ids-at-instagram-1cf5a71e5a5c) 📰 🆓
          * [Sharding and Scaling PostgreSQL: Principles and Practice Webinar](https://www.youtube.com/watch?v=mbXPbLjiYTI) 📼 🆓
          * [Citus vs. Single-Node Postgres Database | A Side-by-Side Comparison](https://www.youtube.com/watch?v=g3H4nGsJsl0) 📼 🆓
          * Replication
            * [Three Approaches to PostgreSQL Replication and Backup](https://www.citusdata.com/blog/2018/02/21/three-approaches-to-postgresql-replication/) 📰 🆓
            * [PostgreSQL Streaming Replication](https://www.youtube.com/watch?v=NaPnYQBBdyU) 📼 🆓
            * [PostgreSQL Replication Concepts](https://www.youtube.com/watch?v=fsMvr96gTjY) 📼 🆓
            * [PostgreSQL Replication by example - Kobus Wolvaardt](https://www.youtube.com/watch?v=5BeC1aD4z8E) 📼 🆓 ⭐️
        * MySQL
          * [Learn to stop using shiny new things and love MySQL](https://medium.com/@Pinterest_Engineering/learn-to-stop-using-shiny-new-things-and-love-mysql-3e1613c2ce14) 📰 🆓
          * [Tracking the Money — Scaling Financial Reporting at Airbnb](https://medium.com/airbnb-engineering/tracking-the-money-scaling-financial-reporting-at-airbnb-6d742b80f040) 📰 🆓
          * [Scaling to 100M: MySQL is a Better NoSQL](https://www.wix.engineering/blog/scaling-to-100m-mysql-is-a-better-nosql) 📰 🆓
          * [Unlocking Horizontal Scalability in Our Web Serving Tier](https://medium.com/airbnb-engineering/unlocking-horizontal-scalability-in-our-web-serving-tier-d907449cdbcf) 📰 🆓
          * [Why Uber Engineering Switched from Postgres to MySQL](https://eng.uber.com/mysql-migration/) 📰 🆓
          * [Evaluating MySQL Parallel Replication Part 4, Annex: Under the Hood](https://medium.com/booking-com-infrastructure/evaluating-mysql-parallel-replication-part-4-annex-under-the-hood-eb456cf8b2fb) 📰 🆓
          * [Mitigating replication lag and reducing read load with freno](https://github.blog/2017-10-13-mitigating-replication-lag-and-reducing-read-load-with-freno/) 📰 🆓
          * [Black-Box Auditing: Verifying End-to-End Replication Integrity between MySQL and Redshift](https://engineeringblog.yelp.com/2018/04/black-box-auditing.html) 📰 🆓
          * [How We Partitioned Airbnb's Main Database in Two Weeks](https://medium.com/airbnb-engineering/how-we-partitioned-airbnb-s-main-database-in-two-weeks-55f7e006ff21)  📰 🆓
          * [Sharding Pinterest: How we scaled our MySQL fleet](https://medium.com/@Pinterest_Engineering/sharding-pinterest-how-we-scaled-our-mysql-fleet-3f341e96ca6f) 📰 🆓
          * [How We Replaced Our Data Pipeline With Zero Downtime](https://www.twilio.com/engineering/2014/06/26/how-we-replaced-our-data-pipeline-with-zero-downtime) 📰 🆓
          * [Vitess: MySQL Sharding - Square Engineering](https://www.youtube.com/watch?v=q65TleTn2vg) 📼 🆓
        * Cassandra
          * [Cassandra at Instagram 2016](https://www.slideshare.net/DataStax/cassandra-at-instagram-2016) 📰 🆓
          * [Cassandra: The Definitive Guide](https://learning.oreilly.com/library/view/cassandra-the-definitive/9781491933657/) 📕 💰
      * NoSQL
        * KeyValue
          * [BoJack](https://github.com/marceloboeira/bojack) ✍🏼 💻 🆓
          * [Why you should build your own NoSQL database](https://medium.com/@marceloboeira/why-you-should-build-your-own-nosql-database-9bbba42039f5) ✍🏼 📰 🆓
          * Redis
            * [Redis Cookbook](https://learning.oreilly.com/library/view/redis-4x-cookbook/9781783988167/) 📕 💰
       * RDS
         * Aurora
           * [Amazon Aurora Multi-Master: Scaling out database write performance (MySQL)](https://www.youtube.com/watch?v=p0C0jakzYuc) 📼 🆓
    * Ledger
      * [What is a Ledger?](https://www.youtube.com/watch?v=BiEbMJ86dGQ) 📼 🆓
      * [Amazon QLDB: An engineer's deep dive on why this is a game changer](https://www.youtube.com/watch?v=ZfYDl4kaVCo) 📼 🆓
    * Distributed Systems
      * Theory
        * [Fallacies of Distributed Computing](https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing) 📰 🆓
        * [Distributed Systems, 2nd Edition](https://learning.oreilly.com/library/view/distributed-systems-2nd/9781466552975/) 📕 💰
        * [Distributed Systems Observability](https://learning.oreilly.com/library/view/distributed-systems-observability/9781492033431/) 📕 💰
        * [Designing Distributed Systems](https://learning.oreilly.com/library/view/designing-distributed-systems/9781491983638/) 📕 💰
        * [Distributed Denial of Service (DDoS)](https://learning.oreilly.com/library/view/distributed-denial-of/9781492026181/) 📕 💰
        * [Distributed Systems Training](https://github.com/pingcap/talent-plan) 📰 🆓
      * Event Sourcing / CQRS
        * [Go Back to the Future with Event Sourcing and CQRS](https://www.youtube.com/watch?v=iGt0DBOWDTs) 📼 🆓
        * [Event Sourcing You are doing it wrong - David Schmitz](https://www.youtube.com/watch?v=GzrZworHpIk) 📼 🆓
        * [The Many Meanings of Event-Driven Architecture - Martin Fowler](https://www.youtube.com/watch?v=STKCRSUsyP0) 📼 🆓
        * [An Introduction to CQRS and Event Sourcing Patterns - Mathew McLoughlin](https://www.youtube.com/watch?v=9a1PqwFrMP0) 📼 🆓
        * [Go Back to the Future with Event Sourcing and CQRS](https://www.youtube.com/watch?v=iGt0DBOWDTs) 📼 🆓
      * Streaming
        * [Kafka](https://kafka.apache.org)
          * [Introduction to Kafka](https://www.youtube.com/watch?v=UEg40Te8pnE) 📼 🆓
          * [Commit Logs in an Age of Microservices - Tim Berglund](https://www.youtube.com/watch?v=bbotWkCLuF0) 📼 🆓
          * [Should you put several event types in the same Kafka topic? - Martin Kleppmann](https://martin.kleppmann.com/2018/01/18/event-types-in-kafka-topic.html) 📰 🆓
          * Practical
            * [Kafka: The Definitive Guide](https://learning.oreilly.com/library/view/kafka-the-definitive/9781491936153/) 📕 💰
          * Internals
            * [The Log: What every software engineer should know about real-time data's unifying abstraction](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying) 📰 🆓
            * [How Kafka's Storage Internals Work](https://thehoard.blog/how-kafkas-storage-internals-work-3a29b02e026) 📰 🆓
            * [Why is Kafka so fast](http://searene.me/2017/07/09/Why-is-Kafka-so-fast/) 📰 🆓
        * NATS
          * [Practical NATS: From Beginner to Pro](https://www.amazon.com/Practical-NATS-Beginner-Waldemar-Quevedo/dp/148423569X) 📕 💰
        * Kinesis
          * ["Distributed Commit Log: Application Techniques for Transaction Processing" by David McNeil](https://www.youtube.com/watch?v=X2g0FFOV2e0) 📼 🆓
        * Commit Log
          * [Commit Logs in an Age of Microservices - Tim Berglund](https://www.youtube.com/watch?v=bbotWkCLuF0) 📼 🆓
          * Build your Own
            * [14-bits/voik](https://github.com/14-bits/voik) 💻 🆓
            * [Corfu - A distributed shared log](https://blog.acolyer.org/2017/05/02/corfu-a-distributed-shared-log/) 📰 🆓
            * [Building a Distributed Message Log from Scratch by Tyler Treat - Video](https://www.youtube.com/watch?v=oKbm9XFxB2k) 📼 🆓
            * [Building a Distributed Log from Scratch, Part 1: Storage Mechanics](https://bravenewgeek.com/building-a-distributed-log-from-scratch-part-1-storage-mechanics/) 📰 🆓
            * [Building a Distributed Log from Scratch, Part 2: Data Replication](https://bravenewgeek.com/building-a-distributed-log-from-scratch-part-2-data-replication) 📰 🆓
            * [Building a Distributed Log from Scratch, Part 3: Scaling Message Delivery](https://bravenewgeek.com/building-a-distributed-log-from-scratch-part-3-scaling-message-delivery/) 📰 🆓
            * [Building a Distributed Log from Scratch, Part 4: Trade-Offs and Lessons Learned](https://bravenewgeek.com/building-a-distributed-log-from-scratch-part-4-trade-offs-and-lessons-learned/) 📰 🆓
            * [Building a Distributed Log from Scratch, Part 5: Sketching a New System](https://bravenewgeek.com/building-a-distributed-log-from-scratch-part-5-sketching-a-new-system/) 📰 🆓
            * Code
              * [travisjeffery/Jocko](https://github.com/travisjeffery/jocko) - Distributed commit log service in Go
              * [zowens/commitlog](http://github.com/zowens/commitlog) - Append-only commit log library for Rust
              * [liftbridge-io/liftbridge](http://github.com/liftbridge-io/liftbridge) - Lightweight, fault-tolerant message streams
            * People to Follow
              * [Tyler Treat](https://twitter.com/tyler_treat?lang=en) 🐦
      * Load Balancing
        * [Taking Zero-Downtime Load Balancing even Further](https://engineeringblog.yelp.com/2017/05/taking-zero-downtime-load-balancing-even-further.html) 📰 🆓
        * [Introducing the GitHub Load Balancer](https://github.blog/2016-09-22-introducing-glb/) 📰 🆓
        * [Improving load balancing with a new consistent-hashing algorithm](https://medium.com/vimeo-engineering-blog/improving-load-balancing-with-a-new-consistent-hashing-algorithm-9f1bd75709ed) 📰 🆓
        * [UDP Load Balancing with Keepalived](https://developers.500px.com/udp-load-balancing-with-keepalived-167382d7ad08) 📰 🆓
        * [Introducing QALM, Uber's QoS Load Management Framework](https://eng.uber.com/qalm/) 📰 🆓
      * Distributed Processing
        * Hadoop
          * [Hadoop: Up & Running](https://learning.oreilly.com/library/view/hadoop-the-definitive/9781491901687/) 📕 💰
      * RPC - Remote Procedure Call
        * [Schema Evolution: AVRO, Protobufs and Thrift](https://martin.kleppmann.com/2012/12/05/schema-evolution-in-avro-protocol-buffers-thrift.html) 📰 🆓
        * [AVRO vs Protobufs vs Thrift](https://www.slideshare.net/IgorAnishchenko/pb-vs-thrift-vs-avro) 📰 🆓
  * Operations
    * Terminal
      * [Set of Bash Oneliners](https://github.com/onceupon/Bash-Oneliner) 💻 🆓
    * Operating Systems
      * Courses
        * [CS8803 - Introduction to Operating Systems](https://eu.udacity.com/course/introduction-to-operating-systems--ud923) 🎓 🆓
            * [Annotations and Exercises](https://github.com/marceloboeira/CS8803) 📝
      * Base Book (Choose 1):
        * [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/) 📕 🆓 ⭐️
        * [Operating System Concepts](https://www.amazon.com/Operating-System-Concepts-Abraham-Silberschatz/dp/1118063333/ref=dp_ob_title_bk) 📕 💰
        * [Operating System Concepts: Essentials](https://www.amazon.com/Operating-Concepts-Essentials-Abraham-Silberschatz/dp/1118804929/ref=sr_1_1?s=books&ie=UTF8&qid=1415311059&sr=1-1&keywords=operating+system+concepts+essentials) 📕 💰
        * [Modern Operating Systems](https://www.amazon.com/Modern-Operating-Systems-4th-Edition/dp/013359162X/ref=dp_ob_title_bk) 📕 💰
      * Computer Architecture
        * [TUHS Lectures](https://minnie.tuhs.org/CompArch/Lectures/) 🆓 📰 🎓
          * [Introduction to Systems Architecture](https://minnie.tuhs.org/CompArch/Lectures/week01.html)
          * [Instruction Set Architecture Design](https://minnie.tuhs.org/CompArch/Lectures/week02.html)
          * [Addressing Modes & CPU Internals](https://minnie.tuhs.org/CompArch/Lectures/week03.html)
          * [Execution Flow, Branches, Function Calls](https://minnie.tuhs.org/CompArch/Lectures/week04.html)
          * [User- and Kernel Mode, System Calls, I/O, Exceptions](https://minnie.tuhs.org/CompArch/Lectures/week05.html)
          * [CPU Memory Management, Context Switching](https://minnie.tuhs.org/CompArch/Lectures/week06.html)
          * [Introduction to Operating Systems](https://minnie.tuhs.org/CompArch/Lectures/week07.html)
          * [Processes](https://minnie.tuhs.org/CompArch/Lectures/week08.html)
          * [Introduction to Memory Management](https://minnie.tuhs.org/CompArch/Lectures/week09.html)
          * [Virtual Memory, Disk Devices](https://minnie.tuhs.org/CompArch/Lectures/week10.html)
          * [Filesystems & Their Performance](https://minnie.tuhs.org/CompArch/Lectures/week11.html)
          * [IPC, Synchronisation and Threads](https://minnie.tuhs.org/CompArch/Lectures/week12.html)
       * File Descriptor
         * [File Descriptors Explained](https://www.youtube.com/watch?v=KM5sRWAYqaw) 📼 🆓
         * [File Descriptors, Unix sockets and other POSIX wizardry - Christian Heimes](https://www.youtube.com/watch?v=Ftg8fjY_YWU) 📼 🆓
         * ["Everything is a file" in UNIX](https://www.youtube.com/watch?v=dDwXnB6XeiA) 📼 🆓
       * Threads
         * ["An Introduction to Programming with Threads"](https://s3.amazonaws.com/content.udacity-data.com/courses/ud923/references/ud923-birrell-paper.pdf) by Birrell 📰 🆓
         * POSIX Threads (PThreads)
           * [PThreads / POSIX Threads Coding Examples](https://computing.llnl.gov/tutorials/pthreads/) 📰 🆓
           * IBM Series
             * [POSIX threads explained: Part 1](https://www.ibm.com/developerworks/library/l-posix1/index.html) 📰 🆓
             * [POSIX threads explained: Part 2](https://www.ibm.com/developerworks/library/l-posix2/index.html) 📰 🆓
             * [POSIX threads explained: Part 3](https://www.ibm.com/developerworks/library/l-posix3/index.html) 📰 🆓
        * [Beyond Multiprocessing: Multithreading the Sun OS Kernel by Eykholt](https://s3.amazonaws.com/content.udacity-data.com/courses/ud923/references/ud923-eykholt-paper.pdf) 📰 🆓
        * [Implementing Lightweight Threads by Stein and Shah](https://s3.amazonaws.com/content.udacity-data.com/courses/ud923/references/ud923-stein-shah-paper.pdf) 📰 🆓
        * [How to create and join threads in C (pthreads)](https://www.youtube.com/watch?v=uA8X5zNOGw8) 📼 🆓
        * [Programming with POSIX ® Threads](https://learning.oreilly.com/library/view/programming-with-posix/0201633922/) 📕 💰
        * CPU Scheduling
          * Timeslice
            * MLFQ - Multi Level Feedback Queue
              * [CPU scheduling Practice - FCFS, SJF, MLFQ](https://www.youtube.com/watch?v=FYcc9D8llF0) 📼 🆓
              * [Multi level queues and multi level feedback queues](https://www.youtube.com/watch?v=1w9FybdNi_Y) 📼 🆓
              * [Designing of vague logic based multilevel feedback queue scheduler](https://www.researchgate.net/publication/283959697_Designing_of_vague_logic_based_multilevel_feedback_queue_scheduler) 🆓 📰
          * Linux
            * O(n), O(1) and CFS
              * [Thread on CFS](https://web.archive.org/web/20120205030735/http://kerneltrap.org/node/11737) 🆓 🌍
              * [The Linux Kernel Scheduler (For Beginners)](https://www.youtube.com/watch?v=5WtnnzpwEuA) 📼 🆓
              * [Operating System #21 Scheduling in Linux: O(n), O(1) Scheduler](https://www.youtube.com/watch?v=vF3KKMI3_1s) 📼 🆓
       * Virtual Memory
         * [The Heap: what does malloc() do?](https://www.youtube.com/watch?v=HPDBOhiKaD8) 📼 🆓
         * mmap
           * [How processes get more memory](https://www.youtube.com/watch?v=XV5sRaSVtXQ) 📼 🆓
           * [How to Map Files into Memory in C (mmap)](https://www.youtube.com/watch?v=m7E9piHcfr4) 📼 🆓
       * Linux
         * [Linux Cross Reference](https://elixir.bootlin.com/linux/v3.17/source/include/linux/kthread.h#L66) 🌍 🆓
         * [Interactive Linux Kernel Map](http://www.makelinux.net/kernel_map/) 🌍 🆓
       * Reference Youtube channels
         * [Jacob Sorber](https://www.youtube.com/channel/UCwd5VFu4KoJNjkWJZMFJGHQ)
    * Network
      * [Computer Networks, 5th Edition](http://www.mypearsonstore.com/bookstore/computer-networks-9780132126953?xid=PSED) 📕 💰
      * Protocols
        * DNS
        * Socket
        * UDP
        * TCP
          * Build Your Own
            * [Implementing TCP in Rust (part 1)](https://www.youtube.com/watch?v=bzja9fQWzdA) 📼 🆓
            * [Implementing TCP in Rust (part 2)](https://www.youtube.com/watch?v=OCpt1I0MWXE) 📼 🆓
            * [Implementing TCP in Rust (part 3)](https://www.youtube.com/watch?v=8GE6ltLRJA4) 📼 🆓
            * [Implementing TCP in Rust (code)](https://github.com/jonhoo/rust-tcp) 🆓
          * SSH
          * HTTP/S
          * SSL-TLS
      * Edge
        * CDN
        * "Global Accelerator"
          * [AWS Global Accelerator Introduction](https://www.youtube.com/watch?v=L-mmnEbiTmc) 📼 🆓
            * 11:00 - Explanation regarding GA
          * [AWS Global Accelerator](https://www.youtube.com/watch?v=YqcEntZ8pQ4) 📼 🆓
    * Monitoring
      * Metrics
        * Prometheus
          * [Prometheus: Up & Running: Infrastructure and Application Performance Monitoring](https://www.amazon.de/gp/product/1492034142?pf_rd_p=99260c3e-e149-406d-b475-c299891fcd91&pf_rd_r=M0874DR76K58PTVG1NV7) 📕 💰
        * InfluxDB
          * [InfluxDB - Time Series Database](https://www.youtube.com/watch?v=2SUBRE6wGiA) 📼 🆓
      * Tracing
        * [Intro to Distributed Tracing](https://www.kartar.net/2019/07/intro-to-distributed-tracing/) 📰 🆓
        * [Mastering Distributed Tracing](https://learning.oreilly.com/library/view/mastering-distributed-tracing/9781788628464/) 📕 💰
    * Infrastructure as Code
      * [What is IaC?](https://www.youtube.com/watch?v=RO7VcUAsf-I) 📼 🆓
      * [Getting Started with IaC](https://www.youtube.com/watch?v=G3D14I5_NIk) 📼 🆓
      * Containers
        * [Docker](https://www.docker.com)
          * Guides
            * [Dockerfile Best Practices - ThoughtWorks](https://blog.docker.com/2019/07/intro-guide-to-dockerfile-best-practices/) 📰 🆓
          * Testing
            * [goss/dgoss](https://github.com/aelsabbahy/goss) - Test docker images ⭐️
              * [marceloboeira/kurz](https://github.com/marceloboeira/kurz) - Example setup ✍🏻
      * Orchestration
        * ECS
          * [ECS Workshop](https://ecsworkshop.com) 👨🏻‍🔧 🆓
        * Kubernetes
          * History
            * [Borg, Omega, and Kubernetes](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/44843.pdf) 📰 🆓
            * [Dockercon keynote: Eric Brewer (Google) - First k8s presentation](https://www.youtube.com/watch?v=YrxnVKZeqK8) 📼 🆓
          * Internals
            * Introduction
              * Microsoft Azure Videos
                * [Why you should care about containers](https://www.youtube.com/watch?v=EUitQ8DaZW8) 📼 🆓
                * [How Kubernetes works](https://www.youtube.com/watch?v=daVUONZqn88) 📼 🆓
                * [How Kubernetes deployments work](https://www.youtube.com/watch?v=mNK14yXIZF4) 📼 🆓
                * [Understand Serverless Kubernetes and Serverless on Kubernetes](https://www.youtube.com/watch?v=xL6lixC4D8Q) 📼 🆓
                * [How the Kubernetes scheduler works](https://www.youtube.com/watch?v=rDCWxkvPlAw) 📼 🆓
                * [Setting up a Kubernetes build pipeline](https://www.youtube.com/watch?v=5irsAdKoEBU) 📼 🆓
                * [Overview of common Kubernetes scenarios](https://www.youtube.com/watch?v=zd8vYhrFXp4) 📼 🆓
                * [How volumes and storage work in Kubernetes](https://www.youtube.com/watch?v=inJ7YJ-jt8I) 📼 🆓
                * [The basics of stateful applications in Kubernetes](https://www.youtube.com/watch?v=GieXzb91I40) 📼 🆓
            * [Understanding Distributed Consensus in etcd and Kubernetes - Laura Frank, CloudBees](https://www.youtube.com/watch?v=n9VKAKwBj_0) 📼 🆓
            * [Kubernetes Deconstructed: Understanding Kubernetes by Breaking It Down - Carson Anderson, DOMO](https://www.youtube.com/watch?v=90kZRyPcRZw) 📼 🆓
            * [Internals Advanced](https://container.training) General talks about containers - 🆓 📼
            * [Kubernetes Up and Running](http://shop.oreilly.com/product/0636920043874.do#tab_04_2) 📕 💰
            * [Key Kubernetes Concepts](https://towardsdatascience.com/key-kubernetes-concepts-62939f4bc08e) 📰 🆓
            * [Programming Kubernetes](https://learning.oreilly.com/library/view/programming-kubernetes/9781492047094/) 📕 💰
            * Networking
              * [A Guide to the Kubernetes Networking Model](https://sookocheff.com/post/kubernetes/understanding-kubernetes-networking-model/) 📰 🆓
              * [How does Traffic Flow inside a Kubernetes Cluster?](https://stackoverflow.com/questions/52241501/how-does-traffic-flow-inside-a-kubernetes-cluster) 📰 🆓
              * Exposing Services
                * [NodePort vs LB vs Ingress](https://medium.com/google-cloud/kubernetes-nodeport-vs-loadbalancer-vs-ingress-when-should-i-use-what-922f010849e0) 📰 🆓
                  * Interesting to understand why ingress is a better option than LB when exposing individual services
                  * LB creates a new IP for every service, it can get expensive and difficult to handle
                  * Ingress can manage multiple domains and paths for many services without difficulty/effort
          * Operators
            * [Introducing Operators](https://coreos.com/blog/introducing-operators.html) 📰 🆓
          * Provider
            * EKS - Elastic Kubernetes Service
              * [EKS - Deep Dive](https://www.youtube.com/watch?v=EDaGpxZ6Qi0) 📼 📼
                  * 08:50 - Control Plane
                  * 10:19 - Control Plane Internals (not shared tenent, endpoints exposed to internet, worker nodes need access to the internet, NLB)
                  * 19:00 - Version Updates
                  * 20:00 - Authentication (IAM -> Authentication | RBAC -> Authorization)
                  * 20:00 - [AMI is OpenSource](https://github.com/awslabs/amazon-eks-ami)
              * [EKS Workshop](https://www.eksworkshop.com) 👨🏻‍🔧 🆓
              * [Custom EKS AMIs](https://aws.amazon.com/premiumsupport/knowledge-center/eks-custom-linux-ami/) 📰 🆓
              * Metrics
                * [EKS + CloudWatch](https://www.youtube.com/watch?v=daLmE0tIcuk) 📼 🆓
                * [EKS + CloudWatch: Container Insights](https://www.youtube.com/watch?v=kn5TVKzBLrU) 📼 🆓
                * [Setup Metrics](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/Container-Insights-setup-metrics.html) 📰 🆓
              * Tracing
                * [AWS X-Ray with EKS](https://aws.amazon.com/blogs/compute/application-tracing-on-kubernetes-with-aws-x-ray/) 📰 🆓
              * Windows
                * [Containerize .NET Apps with Amazon EKS](https://www.youtube.com/watch?v=GIH-MfkZPJA) 📼 🆓
              * Managed Node Groups
                * [EKS Managed Node Groups](https://aws.amazon.com/blogs/containers/eks-managed-node-groups/) 📰 🆓
        * Service Mesh
          * [What is service mesh?](https://www.youtube.com/watch?v=vh1YtWjfcyk) 📼 🆓
          * Istio
            * [Istio Explained - IBM Videos](https://www.youtube.com/watch?v=6zDrLvpfCK4) 📼 🆓
            * [What is Istio? ](https://www.youtube.com/watch?v=1iyFq2VaL5Y) 📼 🆓
              * Nomad
              * Console
            * [Istio: Up & Running](https://learning.oreilly.com/library/view/istio-up-and/9781492043775/) 📕 💰
          * AppMesh
            * [AWS Container Day - App Mesh (Service Mesh Magic)](https://www.youtube.com/watch?v=hfzWtXKrv88) 🆓 📼
            * [AppMesh Workshop](https://www.appmeshworkshop.com) 👨🏻‍🔧🆓
      * Provisioning
        * Terraform
          * [Introduction to Terraform](https://www.youtube.com/watch?v=h970ZBgKINg) 📼 🆓
          * [Infrastructure as Code in the Real World?](https://www.youtube.com/watch?v=S6vS5mzivFo) 📼 🆓
          * [Terraform: Up and Running](https://learning.oreilly.com/library/view/terraform-up-and/9781491977071/) 📕 💰
        * Packer
          * [The Packer Book](https://learning.oreilly.com/library/view/the-packer-book/9780988820272/) 📕 💰
        * [CDK - CloudFormation Development Kit](https://docs.aws.amazon.com/cdk/latest/guide/home.html)
          * [Infrastructure is Code with CDK](https://www.youtube.com/watch?v=ZWCvNFUN-sU&feature=youtu.be) 📼 🆓
    * Linux
      * [LFS - Linux from Scratch Book](http://www.linuxfromscratch.org/lfs/downloads/8.4/LFS-BOOK-8.4.pdf) 📼 🆓
      * systemd
        * [systemd Essentials](https://www.digitalocean.com/community/tutorials/systemd-essentials-working-with-services-units-and-the-journal) 📰 🆓
    * Debug
      * Core Dumps
        * [Debugging with Core Dumps](https://www.youtube.com/watch?v=GV10eIuPs9k) 📼 🆓
    * Performance
      * Profiling
        * Linux Performance
          * [Linux Network Performance Parameters - Leandro Moreira](https://github.com/leandromoreira/linux-network-performance-parameters) 📰 🆓 💻
          * [Linux Performance Hub - Brendan Gregg](http://www.brendangregg.com/linuxperf.html) 📰 🆓 💻
          * [Linux Perf](http://www.brendangregg.com/perf.html) 📰 🆓 💻
          * [Linux Extended BPF (eBPF) Tracing Tools](http://www.brendangregg.com/ebpf.html) 📰 🆓 💻
          * Charts
            * [Linux Performance Observability Tools](http://www.brendangregg.com/Perf/linux_observability_tools.png) 🏙 🆓
            * [Linux Performance Benchmark Tools](http://www.brendangregg.com/Perf/linux_benchmarking_tools.png) 🏙 🆓
            * [Linux Performance Tuning Tools](http://www.brendangregg.com/Perf/linux_tuning_tools.png) 🏙 🆓
          * [Netflix - Linux Systems Performance - Brendan Gregg](https://www.youtube.com/watch?v=CbmEDXq7es0) 📼 🆓
          * [Netflix - Linux Performance - Brendan Gregg](https://www.youtube.com/watch?v=FJW8nGV4jxY) 📼 🆓
          * [How Netflix Tunes Amazon EC2 Instances for Performance - Brendan Gregg](https://www.youtube.com/watch?v=89fYOo1V2pA) 📼 🆓
        * Docker Container
          * [Netflix - Container Performance Analysis](https://www.youtube.com/watch?v=bK9A5ODIgac) 📼 🆓
        * Applications
          * dtrace
            * [DTrace Book Scripts](https://github.com/brendangregg/DTrace-book-scripts) 💻 🆓
          * Rust
            * [Rustt + Dtrace + Flamegraphs](http://carol-nichols.com/2017/04/20/rust-profiling-with-dtrace-on-osx/) 📰 🆓
          * Flamegraph
            * [Tooling to generate FlameGraphs](https://github.com/brendangregg/FlameGraph) 💻 🆓
            * [Deep dive to CPU FlameGraphs](http://www.brendangregg.com/FlameGraphs/cpuflamegraphs.html) 📰 💻 🆓
            * [Speedscope - visualization tool](http://jamie-wong.com/post/speedscope/) 💻 🆓
            * [Presentation on FlameGraphs](https://speakerdeck.com/mrfoto/what-are-flame-graphs-and-how-to-read-them) 🎥 🆓
  * Security
    * Firewall
      * WAF - Web Application Firewall
        * [What is a Web Application Firewall (WAF)?](https://www.youtube.com/watch?v=p8CQcF_9280) 📼 🆓
        * [The AWS Web Application Firewall (WAF)](https://youtu.be/SmF_wQuZ7z4) 📼 🆓
