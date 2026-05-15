---
layout: about
title: About
show_clustrmap: true
permalink: /
subtitle: Founding Engineer at Netpreme | Ph.D., HKUST

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

I am a founding engineer at [Netpreme](https://www.netpreme.com/), where we build next-generation computer systems to break the memory wall for AI.

I received my Ph.D. from [The Hong Kong University of Science and Technology (HKUST)](https://www.ust.hk/), where I was advised by [Prof. Kai Chen](http://www.cse.ust.hk/~kaichen/). Before that, I earned my B.Eng. in Software Engineering from [Wuhan University](https://www.whu.edu.cn/) in 2020, graduating as an Outstanding Graduate.

<!-- My research interests include system for LLMs, data center networking, congestion control and distributed system.  -->

My research focuses on building high-performance systems that bridge applications, algorithms, and hardware. In particular, I work on:

- application-aware optimization for distributed systems. I design systems that push the hardware-software boundary by tailoring architectures and algorithms to workload behavior:
  - [MixNet](https://xudongliao.github.io/assets/pdf/mixnet-sigcomm25.pdf) (SIGCOMM'25) is a runtime-reconfigurable optical-electrical fabric for distributed Mixture-of-Experts training. It exploits dynamic, sparse, and localized traffic patterns to adapt topology on the fly, enabling scalable and cost-efficient training across thousands of GPUs while maintaining near-ideal training speed.
  - [Herald](https://xudongliao.github.io/assets/pdf/herald-nsdi24.pdf) (NSDI'24) is an embedding-aware scheduler for DLRM training. It leverages predictable and infrequent in-cache embedding access patterns to eliminate a substantial portion of communication overhead and accelerate training.
  - [Pallas](https://xudongliao.github.io/assets/pdf/pallas-atc25.pdf) (ATC'25) is a rack-scale CPU scheduling system that combines switch programmability with request-level predictability to enable efficient in-network workload shaping and achieve near-optimal microsecond-level tail latency.

- practical, high-performance learning-based congestion control. This line of work includes [MOCC](https://xudongliao.github.io/assets/pdf/mocc-eurosys22.pdf) (EuroSys'22), [Spine](https://xudongliao.github.io/assets/pdf/spine-conext22.pdf) (CoNEXT'22), [Astraea](https://xudongliao.github.io/assets/pdf/astraea-eurosys24.pdf) (EuroSys'24), [Jury](https://xudongliao.github.io/assets/pdf/jury-eurosys25.pdf) (EuroSys'25), [Learn-to-Probe](https://xudongliao.github.io/assets/pdf/ltp-eurosys26.pdf) (EuroSys'26), and [PolicyCache](https://xudongliao.github.io/assets/pdf/policycache-nsdi26.pdf) (NSDI'26). Across these projects, we address challenges such as multi-objective optimization, runtime overhead, fairness, convergence, signal distinguishability, and performance generalization, with the goal of making learning-driven transport practical in real deployments.

During my time at WHU, I was fortunate to be advised by [Prof. Yanjiao Chen](https://person.zju.edu.cn/en/0020875). I have also had the opportunity to collaborate closely with [Prof. Guyue Liu](https://grace-liu.github.io) from Peking University and [Dr. Zhizhen Zhong](https://zhizhenzhong.com/) from MIT on several recent projects.

#### Research Interests

- Machine Learning Systems
- Datacenter Networking
- Congestion Control
- Optical Networking
