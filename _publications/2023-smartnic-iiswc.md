---
title: "Making Sense of Using a SmartNIC to Reduce Datacenter Tax from SLO and TCO Perspectives"
collection: publications
permalink: /publication/2023-smartnic-iiswc
excerpt: 'Jinghan Huang, Jiaqi Lou, Yan Sun, Tianchen Wang, Eun Kyung Lee, Nam Sung Kim. [paper](https://ieeexplore.ieee.org/abstract/document/10289567)'
date: '2023.10.1'
venue: 'IISWC'
---

The speed of network interfaces has rapidly increased, while the performance and energy efficiency of CPUs have not, due to the demise of Dennard scaling. As a result, functions processing network packets have become responsible for a rapidly increasing portion of the datacenter tax. To tackle this problem, the industry has developed SmartNICs (SNICs) integrating conventional NICs with inexpensive and energy-efficient processors that can efficiently execute functions widely used by network-intensive datacenter applications. With such processors, the SNICs promise to reduce the total cost of ownership (TCO) for datacenters by increasing energy efficiency of servers and/or decreasing the number of expensive server CPU cores. In this paper, to make sense of using SNICs, we focus on analyzing energy efficiency of a server with an SNIC, especially under service level objective (SLO) constraints which matter for many datacenter applications. To this end, we not only measure the system-wide power consumption of a server but also devise a custom hardware setup that allows us to isolate the power consumption of the SNIC from that of the server. This helps us better understand the impact of using SNICs on energy efficiency of servers. Second, we take popular TCP/UDP, DPDK, and RDMA-based functions, and prepare them to run on an SNIC processor and a server CPU. Then, we measure maximum throughput, tail latency, system-wide energy efficiency of executing the functions on the SNIC processor and the server CPU, respectively. Lastly, based on analyses of the measurements, we make five key observations and three strategies to better use and design SmartNICs in the future.

[paper](https://ieeexplore.ieee.org/abstract/document/10289567) 
