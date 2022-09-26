---
title: "xRSA: Construct Larger Bits RSA on Low-Cost Devices"
authors:
- admin
- Lingkun Li
- Jiajie Chen
date: "2021-12-14T00:00:00Z"
doi: "10.1109/ICPADS53394.2021.00085"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 27th IEEE International Conference on Parallel and Distributed Systems*
publication_short: In *IEEE ICPADS 2021*

abstract: As the most widely applied public-key cryptographic algorithm, RSA is now integrated into many low-cost devices such as IoT devices. Due to the limited resource, most low-cost devices only ship a 2048-bit multiplier, making the longest supported private key length as 2048 bits. Unfortunately, 2048-bit RSA keys are gradually considered insecure. Utilizing the existing 2048-bit multiplier is challenging because a 4096-bit message cannot be stored in the multiplier. In this paper, we perform a thorough study of RSA and propose a new method that achieves the 4096-bit RSA cryptography with the existing hardware. We use the Montgomery modular multiplication and the Chinese Remainder Theorem to reduce the computational cost and construct the necessary components to compute the RSA private key operation. To further validate the correctness of the method and evaluate its performance, we implement this method on a micro-controller and build a testbed named CanoKey with three commonly used cryptography protocols. The result shows that our method is over 200x faster than the naïve method, a.k.a., software-based big number multiplications.

# Summary. An optional shortened abstract.
# summary: 

featured: true
url_slides: 'publication/icpads21-xrsa/icpads21-xrsa-slides.pdf'
url_video: 'https://youtu.be/qikDbr9ej1g'

---
