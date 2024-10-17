---
title: "InNetScheduler: In-network scheduling for time- and event-triggered critical traffic in TSN"
authors:
- Xiangwen Zhuge
- Xinjun Cai
- Xiaowu He
- Zeyu Wang
- admin
- Xu Wang
- Zheng Yang
date: "2024-05-20T00:00:00Z"
doi: "10.1109/INFOCOM52122.2024.10621265"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 43rd Annual IEEE International Conference on Computer Communications*
publication_short: In *IEEE INFOCOM 2024*

abstract: "Time-Sensitive Networking (TSN) is an enabling technology for Industry 4.0. Traffic scheduling plays a key role for TSN to ensure low-latency and deterministic transmission of critical traffic. As industrial network scales, TSN networks are expected to support a rising number of both time-triggered and event-triggered critical traffic (TCT and ECT). In this work, we present InNetScheduler, the first in-network TSN scheduling paradigm that boosts the throughput, i.e., number of scheduled data flows, of both traffic types. Different from existing approaches that conduct entire scheduling on the server, InNetScheduler leverages the computation resources on switches to promptly schedule latency-critical ECT, and delegate the computational-intensive TCT scheduling to server. The key innovation of InNetScheduler includes a Load-Aware Optimizer to mitigate ECT conflicts, a Relaxated ECT Scheduler to accelerate in-network computation, and End-to-End Determinism Guarantee to lower scheduling jitter. We fully implement a suite of InNetScheduler-compatible TSN switches with hardwaresoftware co-design. Extensive experiments are conducted on both simulation and physical testbeds, and the results demonstrate InNetScheduler’s superior performance. By unleashing the power of in-network computation, InNetScheduler points out a direction to extend the capacity of existing industrial networks."

featured: false

---
