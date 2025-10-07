---
title: "HINT: A Hardware Platform for Intra-host NIC Traffic and SmartNIC Emulation"
collection: publications
permalink: /publication/2025-hint-cal
excerpt: '**Jiaqi Lou**\*, Yu Li\*, Srikar Vanavasam, Nam Sung Kim. <br /> [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11048525){: .btn--research}'
date: '2025.4'
venue: 'CAL'
paperurl: https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11048525
---

[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11048525)


Recent performance advancements in inter-host networking demand innovations in intra-host communication and SmartNICaccelerated in-network processing. However, developing novel SmartNIC features remains difficult due to absence of hardware observability and low-cost, deterministic testing environments with existing software-based or commercial development platforms. While FPGA-based SmartNICs offer high flexibility and performance for packet processing acceleration, existing solutions support only a limited subset of network technologies widely used in commercial datacenters. To address these challenges, we introduce HINT, an FPGA-based development and emulation platform that transparently mimics a commercial SmartNIC in the system, featuring controlled network traffic generation with a high-performance traffic engine and kernel-bypass network technologies. It also supports configurable workload patterns, nanosecond-level latency measurement, and a reconfigurable Receive Side Scaling (RSS) engine for load balancing. Our evaluation shows that HINT achieves 91% of PCIe’s theoretical efficiency, providing a highly effective and scalable platform to emulate an end-to-end system with support for diverse network stacks. HINT thus establishes an accessible, high-fidelity platform for SmartNIC development and emulation, along with architectural exploration of intra-host communication.