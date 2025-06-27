---
title: "LADIO: Leakage-Aware Direct I/O for I/O-Intensive Workloads"
collection: publications
permalink: /publication/2023-ladio-cal
excerpt: 'Ipoom Jeong, **Jiaqi Lou**, Yongseok Son, Yongjoo Park, Yifan Yuan, Nam Sung Kim. <br /> [paper](https://ieeexplore.ieee.org/abstract/document/10171430){: .btn--research}'
date: '2023.7.3'
venue: 'IEEE Computer Architecture Letters'
paperurl: https://ieeexplore.ieee.org/abstract/document/10171430
---

[paper](https://ieeexplore.ieee.org/abstract/document/10171430) 

The advancement in I/O technology has posed an unprecedented demand for high-performance processing on I/O data, leading to the development of Data Direct I/O (DDIO) technology. DDIO improves I/O processing efficiency by directly injecting all inbound I/O data into the last-level cache (LLC) in cooperation with any type of I/O device. Nonetheless, in certain scenarios with more than one I/O applications, DDIO may have sub-optimal performance caused by interference inside the LLC, resulting in the degradation of system performance. Especially, in this paper, we demonstrate that storage I/O on modern high-performance NVMe SSDs hardly benefits from DDIO, sometimes causing inefficient use of the shared LLC due to the “leaky DMA problem”. To address this problem, we propose LADIO , an adaptive approach that mitigates inter-application interference by dynamically controlling the DDIO functionality and reallocating LLC ways based on the leakage and locality of storage I/O data, respectively. In scenarios with heavy I/O interference, LADIO improves the throughput of network-intensive applications by 20% while maintaining that of storage-intensive applications.

