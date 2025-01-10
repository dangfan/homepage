---
title: "6Loda: Pattern Filtering and Ensemble Learning for IPv6 Target Generation and Scanning"
authors:
- Xikai Sun
- admin
- Zihao Yang
- Xinqi Jin
- Junhao Li
- Yunhao Liu
date: "2025-01-10T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 44th Annual IEEE International Conference on Computer Communications*
publication_short: In *IEEE INFOCOM 2025*

abstract: "IPv6 target generation is crucial for surveying the vast IPv6 address space, which is essential for network management and IPv6 deployment policies. However, existing techniques often suffer from low hit rates due to ineffective space partitioning caused by outlier addresses and limitations in current outlier removal algorithms. To address these challenges, we propose 6Loda, a novel approach that combines pattern filtering and ensemble learning to efficiently remove outlier addresses and discover active IPv6 addresses. Given a set of known active addresses, 6Loda first employs a pattern-based filter to preliminarily eliminate some outlier addresses. It then utilizes a two-level (divisive hierarchical clustering) DHC algorithm to partition the seed set and applies the Loda algorithm to automatically remove remaining outliers in address spaces. Finally, 6Loda implements the random generation algorithm to produce addresses with high hit rates. Experiments conducted on large-scale datasets demonstrate that 6Loda achieves a ×2.26 improvement in hit rate compared to state-of-the-art methods, while maintaining the same budget constraints."

featured: false

---
