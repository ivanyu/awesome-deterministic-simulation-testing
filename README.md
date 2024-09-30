# Awesome Deterministic Simulation Testing
A curated list of awesome deterministic simulation testing resources.

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Case studies and blogs

### 🎞️ ["Testing Distributed Systems w/ Deterministic Simulation" by Will Wilson](https://www.youtube.com/watch?v=4fFDFbi3toc)
An overview of the deterministic simulation testing in FoundationDB, influential for many following cases.

### [BUGGIFY](https://transactional.blog/simulation/buggify)
An overview of `BUGGIFY` macro from FoundationDB.

### [What's the big deal about Deterministic Simulation Testing?](https://notes.eatonphil.com/2024-08-20-deterministic-simulation-testing.html)

### [(Mostly) Deterministic Simulation Testing in Go](https://www.polarsignals.com/blog/posts/2024/05/28/mostly-dst-in-go)
> How we used WASM and some Go runtime modifications to run deterministic simulation tests against FrostDB

### [sled simulation guide (jepsen-proof engineering)](https://sled.rs/simulation.html)

> This guide contains basic information about deterministic testing of distributed, message-based, event-driven, or actor systems.

### A blog series on Deterministic simulation from RisingWave

[Deterministic Simulation: A New Era of Distributed System Testing (Part 1 of 2)](https://risingwave.com/blog/deterministic-simulation-a-new-era-of-distributed-system-testing/)

> This article discusses the background and principles of deterministic simulation, introduce our deterministic testing framework Madsim, and share our experience applying deterministic testing to RisingWave.

[Applying Deterministic Simulation: The RisingWave Story (Part 2 of 2)](https://risingwave.com/blog/applying-deterministic-simulation-the-risingwave-story-part-2-of-2/)

> Delve into the world of deterministic simulation as we introduce Madsim, a cutting-edge testing framework built on Rust's asynchronous programming ecosystem. Join us in this article as we unravel the fascinating utilization of deterministic simulation in RisingWave, a cloud-native distributed database.

### [Testing sync at Dropbox](https://dropbox.tech/infrastructure/-testing-our-new-sync-engine)

> … and how we rewrote the heart of sync with confidence.

### Case studies of Antithesis
- [Deterministic Simulation Testing for Our Entire SaaS](https://www.warpstream.com/blog/deterministic-simulation-testing-for-our-entire-saas).
- [Chaos Testing Stardog Cluster for Fun and Profit](https://www.stardog.com/labs/blog/chaos-testing-stardog-cluster-for-fun-and-profit/).
- [Accelerating developers at MongoDB](https://antithesis.com/case_studies/mongodb_productivity/).
- [Testing the Ethereum merge](https://antithesis.com/case_studies/ethereum_merge/).


### [Deterministic Simulation Testing at TigerBeetle](https://docs.tigerbeetle.com/about/vopr)

> Deterministic Simulation Testing (DST) is one of our favorite parts about TigerBeetle, and it is a key way that we improve the system's reliability.

### [Deterministic Simulation Testing at Resonate](https://blog.resonatehq.io/deterministic-simulation-testing)

> At Resonate, we consider deterministic simulation testing (DST) to be a cornerstone of our mission to build correct and reliable distributed systems. While an increasing array of projects, including Foundation DB, TigerBeetle DB, and Resonate itself, have embraced DST, along with companies like Antithesis providing platforms dedicated to this approach, comprehensive information remains limited.

### [Hiisi](https://github.com/penberg/hiisi) by Pekka Enberg

> Hiisi is a proof of concept libSQL written in Rust following TigerBeetle-style with deterministic simulation testing.

The [Twitter thread](https://x.com/penberg/status/1821888879718281303).

## Software

### [Antithesis](https://antithesis.com/)

> Antithesis is a continuous reliability platform that autonomously searches for problems in your software within a simulated environment. Every problem we find can be perfectly reproduced, allowing for efficient debugging of even the most complex problems.

### [MadSim](https://github.com/madsim-rs/madsim)

A deterministic simulator for distributed systems in Rust.

[MadRaft](https://github.com/madsim-rs/madraft) - the labs of Raft consensus algorithm based on MadSim.

### [Turmoil](https://github.com/tokio-rs/turmoil)
A framework for testing distributed systems, which provides deterministic execution by running multiple concurrent hosts within a single thread.
