---
layout: about
title: About
show_clustrmap: true
permalink: /
subtitle: PhD Candidate, HKUST, Hong Kong SAR, China

profile:
  align: right
  image: xudong.jpg
  image_circular: false # crops the image to make it circular
  more_info: >

news: true # includes a list of news items
latest_posts: false # includes a list of the newest posts
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---

I am a Ph.D candidate in [Hong Kong University of Science and Technology (HKUST)](https://www.ust.hk/), advised by [Prof. Kai Chen](http://www.cse.ust.hk/~kaichen/). Before that, I received my B.Eng in Software Engineering in [Wuhan University](https://www.whu.edu.cn/) (Outstanding Graduate) in 2020.

<!-- My research interests include system for LLMs, data center networking, congestion control and distributed system.  -->

In my research projects, I focus on:

- application-aware optimizations for distributed systems. I build systems that push the hardware–software boundary by tailoring architectures and algorithms to each workload’s unique behavior:
  - [MixNet](https://xudongliao.github.io/assets/pdf/mixnet-sigcomm25.pdf) (SIGCOMM'25) – a runtime reconfigurable optical–electrical fabric that leverages the dynamic, sparse and localized traffic patterns in distributed Mixture-of-Experts training to regionally adapt its topology on-the-fly, enabling scalable and cost-efficient training across thousands of GPUs—with near-ideal training speed and significantly reduced networking costs.
  - [Herald](https://xudongliao.github.io/assets/pdf/herald-nsdi24.pdf) (NSDI'24) – an embedding-aware scheduler that exploits the predictable and infrequent in-cache embedding access patterns of DLRM training to schedule the embedding access, eliminating a substantial portion of communication and efficiently speeding up the training.
  - [Pallas](https://xudongliao.github.io/assets/pdf/pallas-atc25.pdf) (ATC'25) – an rack-scale CPU scheduling system that utilizes switch programmability and request-level predictability to enable efficient in-network workload shaping, driving near-optimal microsecond-level tail latency.

- designing performant and practical DRL-driven CC algorithms – including [MOCC](https://xudongliao.github.io/assets/pdf/mocc-eurosys22.pdf) (EuroSys'22), [Spine](https://xudongliao.github.io/assets/pdf/spine-conext22.pdf) (CoNEXT'22), [Astraea](https://xudongliao.github.io/assets/pdf/astraea-eurosys24.pdf) (EuroSys'24), and [Jury](https://xudongliao.github.io/assets/pdf/jury-eurosys25.pdf) (EuroSys'25). These projects tackle key obstacles such as multi-objectives, overhead, fairness & convergence, and performance generalizability, paving the way for real-world deployment of DRL-based transport protocols.

I was fortunate to be advised by [Prof. Yanjiao Chen](https://person.zju.edu.cn/en/0020875) during my time at WHU. Additionally, I am fortunate to collaborate closely with [Prof. Guyue Liu](https://grace-liu.github.io) from Peking University and [Dr. Zhizhen Zhong](https://zhizhenzhong.com/) from MIT on several recent projects.

#### Research Interests

- Machine Learning System
- Datacenter Networking
- Congestion Control
- Optical Network
