---
title: "DeepScheduler: Enabling Flow-Aware Scheduling in Time-Sensitive Networking"
authors:
- Xiaowu He
- Xiangwen Zhuge
- admin
- Xu Wang
- Zheng Yang
date: "2023-01-20T00:00:00Z"
doi: "10.1109/INFOCOM53939.2023.10228875"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 42nd Annual IEEE International Conference on Computer Communications*
publication_short: In *IEEE INFOCOM 2023*

abstract: "Time-Sensitive Networking (TSN) has been considered the most promising network paradigm for time-critical applications (e.g., industrial control) and traffic scheduling is the core of TSN to ensure low latency and determinism. With the demand for flexible production increases, industrial network topologies and settings change frequently due to pipeline switches. As a result, there is a pressing need for a more efficient TSN scheduling algorithm. In this paper, we propose DeepScheduler, a fast and scalable flow-aware TSN scheduler based on deep reinforcement learning. In contrast to prior work that heavily relies on expert knowledge or problem-specific assumptions, DeepScheduler automatically learns effective scheduling policies from the complex dependency among data flows. We design a scalable neural network architecture that can process arbitrary network topologies with informative representations of the problem, and decompose the problem decision space for efficient model training. In addition, we develop a suite of TSN-compatible testbeds with hardware-software co-design and DeepScheduler integration. Extensive experiments on both simulation and physical testbeds show that DeepScheduler runs >150/5 times faster and improves the schedulability by 36%/39% compared to state- of-the-art heuristic/expert-based methods. With both efficiency and effectiveness, DeepScheduler makes scheduling no longer an obstacle towards flexible manufacturing."

featured: false

---
