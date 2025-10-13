---
title: "Palantir: Towards Efficient Super Resolution for Ultra-high-definition Live Streaming"
authors:
- Xinqi Jin
- Zhui Zhu
- Xikai Sun
- Fan Dang
- Jiangchuan Liu
- Jingao Xu
- Kebin Liu
- Xinlei Chen
- Yunhao Liu
date: "2025-03-31T00:00:00Z"
doi: "10.1145/3712676.3714434"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 16th ACM Multimedia Systems Conference*
publication_short: In *ACM MMSys 2025*

abstract: Neural enhancement through super-resolution (SR) deep neural networks (DNNs) opens up new possibilities for ultra-high-definition (UHD) live streaming. Yet, the heavy SR DNN inference overhead leads to severe deployment challenges. To reduce the overhead, existing systems propose to apply DNN-based SR only on carefully selected anchor frames while upscaling non-anchor frames via the lightweight reusing-based SR approach. However, frame-level scheduling is coarse-grained and fails to deliver optimal efficiency. In this work, we propose Palantír, the first neural-enhanced UHD live streaming system with fine-grained patch-level scheduling. At the core of Palantír is its SR video quality estimation strategy which guides the low-delay selection of the most beneficial anchor patches. Although existing systems propose estimation strategies for anchor frame selection, these strategies heavily rely on empirical insights that cannot be transferred to our context, making fine-grained scheduling a challenging problem that requires a fundamentally new solution. Facing the challenge, we follow the first-principles approach and derive a directed acyclic graph (DAG) model to address the problem. The model can also be generalized to various settings due to its first-principles nature. Compared to the state-of-the-art real-time frame-level scheduling strategy for live streaming, Palantír reduces the anchor size by 80.1% at most and 38.4% on average without compromising the quality gain. Furthermore, Palantír incurs a scheduling latency accounting for only 0.6-3.9% of the end-to-end latency requirement for UHD live streaming.

featured: false

---
