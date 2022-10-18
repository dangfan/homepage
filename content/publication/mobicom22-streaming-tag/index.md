---
title: "StreamingTag: A Scalable Piracy Tracking Solution for Mobile Streaming Services"
authors:
- Xinqi Jin
- admin
- Qi-An Fu
- Lingkun Li
- Guanyan Peng
- Xinlei Chen
- Kebin Liu
- Yunhao Liu
date: "2022-10-14T00:00:00Z"
doi: "10.1145/3495243.3560521"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 28th Annual International Conference On Mobile Computing And Networking*
publication_short: In *ACM MobiCom 2022*

abstract: Streaming services have billions of mobile subscribers, yet video piracy has cost service providers billions. Digital Rights Management (DRM), however, is still far from satisfactory. Unlike DRM, which attempts to prohibit the creation of pirated copies, fingerprinting may be used to track out the source of piracy. Nevertheless, the idea of piracy tracing is not widely used at the moment, since existing fingerprinting-based streaming systems fail to serve numerous users. In this paper, we present the design and evaluation of StreamingTag, a scalable piracy tracing system for mobile streaming services. StreamingTag adopts a segment-level fingerprint embedding scheme to remove the need of re-embedding the fingerprint into the video for each new viewer. The key innovations of StreamingTag include a scalable and CDN-friendly delivery framework, a polarized and randomized SVD watermarking scheme suitable for short segments, and a collusion-resistant fingerprinting scheme optimized for large-scale streaming services. Experiment results show the good QoS of StreamingTag in terms of preparation latency, bandwidth consumption, and video fidelity. Compared with existing SVD watermarking schemes, the proposed watermarking scheme improves the watermark extraction accuracy by 2.25x at most and 1.5x on average. Compared with existing collusion-resistant fingerprinting schemes, the proposed scheme catches more colluders and improves the recall rate by 26%.

featured: true

---
