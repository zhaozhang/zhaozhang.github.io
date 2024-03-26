---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

- [NeurIPS'23] Mozaffari, Mohammad, Sikan Li, Zhao Zhang, and Maryam Mehri Dehnavi. ["MKOR: Momentum-Enabled Kronecker-Factor-Based Optimizer Using Rank-1 Updates"](https://arxiv.org/abs/2306.01685) to appear in NeurIPS'23.
- [SC'23-1] Q. Ding, P. Zheng, S. Kudari, S. Venkataraman, Z. Zhang. ["Mirage: Towards Low-interruption Services on Batch GPU Clusters with Reinforcement Learning"](https://arxiv.org/abs/2306.14086) to appear in SC'23.
- [SC'23-2] E. Karrels, L. Huang, Y. Kan, I. Arora, Y. Wang, D. S. Katz, B. D. Gropp, Z. Zhang. ["Fine-grained Policy-driven I/O Sharing for Burst Buffers"](https://arxiv.org/abs/2306.11615) to appear in SC'23.
- [TPDS'22] J. G. Pauloski, L. Huang, W. Xu, I. T. Foster, Z. Zhang. ["Deep Neural Network Training with Distributed K-FAC"](https://ieeexplore.ieee.org/document/9739867) in IEEE Transactions on Parallel and Distributed Systems, doi: 10.1109/TPDS.2022.3161187.
- [SC'21] J. G. Pauloski, Q. Huang, L. Huang, S. Venkataraman, K. Chard, I. T. Foster, Z. Zhang. ["KAISA: An Adaptive Second-order Optimizer Framework for Deep Neural Networks"](https://arxiv.org/pdf/2107.01739.pdf) In Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis, pp. 1-14. 2021.
- [Nature Methods'21] Fang, Linjing, Fred Monroe, Sammy Weiser Novak, Lyndsey Kirk, Cara R. Schiavon, Seungyoon B. Yu, Tong Zhang et al. ["Deep learning-based point-scanning super-resolution imaging."](https://www.nature.com/articles/s41592-021-01080-z) Nature methods 18, no. 4 (2021): 406-416.
- [SC'20] J. G. Pauloski, Z. Zhang, L. Huang, W. Xu, I. T. Foster. ["Convolutional Neural Network Training with Distributed K-FAC"](https://dl.acm.org/doi/abs/10.5555/3433701.3433826) In Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis, pp. 1-14. 2020.
- [IPDPS'20] Z. Zhang, L. Huang, J. G. Pauloski, I. T. Foster. ["Efficient I/O for Neural Network Training with Compressed Data"](https://ieeexplore.ieee.org/abstract/document/9139800/) In 2020 IEEE International Parallel and Distributed Processing Symposium (IPDPS), pp. 409-418. IEEE, 2020.
- [CLUSTER'19] Z. Zhang, L. Huang, R. Huang, W. Xu, D. S. Katz. ["Quantifying the Impact of Memory Errors in Deep Learning."](https://ieeexplore.ieee.org/document/8890989) In 2019 IEEE International Conference on Cluster Computing (CLUSTER), p.1. IEEE, 2019.
- [TPDS'19] Y. You, Z. Zhang, J. Demmel, K. Keutzer, C. Hsieh. ["Fast Deep Neural Network Training on
Distributed Systems and Cloud TPUs."](https://ieeexplore.ieee.org/document/8703162) IEEE Transactions on Parallel and Distributed Systems 30, no. 11 (2019): 2449-2462.
