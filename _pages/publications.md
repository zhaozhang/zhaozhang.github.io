---
layout: archive
#title: "Publications"
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

### Highlighted Recent Papers
- [NeurIPS'23] Mozaffari, Mohammad, Sikan Li, Zhao Zhang, and Maryam Mehri Dehnavi. ["MKOR: Momentum-Enabled Kronecker-Factor-Based Optimizer Using Rank-1 Updates."](https://arxiv.org/abs/2306.01685). Advances in Neural Information Processing Systems 36 (2024)..
- [SC'23] Q. Ding, P. Zheng, S. Kudari, S. Venkataraman, Z. Zhang. ["Mirage: Towards Low-interruption Services on Batch GPU Clusters with Reinforcement Learning."](https://arxiv.org/abs/2306.14086)  In Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis, pp. 1-13. 2023.
- [SC'23] E. Karrels, L. Huang, Y. Kan, I. Arora, Y. Wang, D. S. Katz, B. D. Gropp, Z. Zhang. ["Fine-grained Policy-driven I/O Sharing for Burst Buffers."](https://arxiv.org/abs/2306.11615) In Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis, pp. 1-12. 2023.
- [TPDS'22] J. G. Pauloski, L. Huang, W. Xu, I. T. Foster, Z. Zhang. ["Deep Neural Network Training with Distributed K-FAC."](https://ieeexplore.ieee.org/document/9739867) in IEEE Transactions on Parallel and Distributed Systems, doi: 10.1109/TPDS.2022.3161187.
- [SC'21] J. G. Pauloski, Q. Huang, L. Huang, S. Venkataraman, K. Chard, I. T. Foster, Z. Zhang. ["KAISA: An Adaptive Second-order Optimizer Framework for Deep Neural Networks."](https://arxiv.org/pdf/2107.01739.pdf) In Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis, pp. 1-14. 2021.
- [Nature Methods'21] Fang, Linjing, Fred Monroe, Sammy Weiser Novak, Lyndsey Kirk, Cara R. Schiavon, Seungyoon B. Yu, Tong Zhang et al. ["Deep learning-based point-scanning super-resolution imaging."](https://www.nature.com/articles/s41592-021-01080-z) Nature methods 18, no. 4 (2021): 406-416.
- [SC'20] J. G. Pauloski, Z. Zhang, L. Huang, W. Xu, I. T. Foster. ["Convolutional Neural Network Training with Distributed K-FAC"](https://dl.acm.org/doi/abs/10.5555/3433701.3433826) In Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis, pp. 1-14. 2020.
- [IPDPS'20] Z. Zhang, L. Huang, J. G. Pauloski, I. T. Foster. ["Efficient I/O for Neural Network Training with Compressed Data"](https://ieeexplore.ieee.org/abstract/document/9139800/) In 2020 IEEE International Parallel and Distributed Processing Symposium (IPDPS), pp. 409-418. IEEE, 2020.
- [CLUSTER'19] Z. Zhang, L. Huang, R. Huang, W. Xu, D. S. Katz. ["Quantifying the Impact of Memory Errors in Deep Learning."](https://ieeexplore.ieee.org/document/8890989) In 2019 IEEE International Conference on Cluster Computing (CLUSTER), p.1. IEEE, 2019.
- [TPDS'19] Y. You, Z. Zhang, J. Demmel, K. Keutzer, C. Hsieh. ["Fast Deep Neural Network Training on
Distributed Systems and Cloud TPUs."](https://ieeexplore.ieee.org/document/8703162) IEEE Transactions on Parallel and Distributed Systems 30, no. 11 (2019): 2449-2462.

### Other Papers
- [ISC'21] Evans, Richard Todd, Matthew Cawood, Stephen Lien Harrell, Lei Huang, Si Liu, Chun-Yaung Lu, Amit Ruhela, Yinzhi Wang, and Zhao Zhang. ["Optimizing GPU-Enhanced HPC System and Cloud Procurements for Scientific Workloads."](https://link.springer.com/chapter/10.1007/978-3-030-78713-4_17) In International Conference on High Performance Computing, pp. 313-331. Springer, Cham, 2021.
- [ICPP'18] Y. You, Z. Zhang, J. Demmel, K. Keutzer, C. Hsieh. ["ImageNet Training in Minutes."](https://dl.acm.org/citation.cfm?id=3225069) In Proceedings of the 47th International Conference on Parallel Processing, p. 1. ACM, 2018. Best Paper Award.
- [HPDC'17] Z. Zhang, E. R. Sparks, and M. J. Franklin. ["Diagnosing machine learning pipelines with fine-grained lineage."](https://dl.acm.org/citation.cfm?id=3078603) In Proceedings of the 26th International Symposium on High-Performance Parallel and Distributed Computing, pp. 143-153. ACM, 2017.
- [FGCS'16] D. S. Katz, A. Merzky, Z. Zhang, S. Jha. ["Application Skeletons: Construction and Use in eScience."](https://www.sciencedirect.com/science/article/pii/S0167739X15003143) Future Generation Computer Systems 59 (2016): 114-124.
- [IPDPS'16] M. Turilli, F. Liu, Z. Zhang, A. Merzky, M. Wilde, J. Weissman, D. S. Katz, and S. Jha. ["Integrating abstractions to enhance the execution of distributed applications."](https://ieeexplore.ieee.org/abstract/document/7516092/) In 2016 IEEE International Parallel and Distributed Processing Symposium (IPDPS), pp. 953-962. IEEE, 2016.
- [BigData'16] Z. Zhang, K. Barbary, F. A. Nothaft, E. R. Sparks, O. Zahn, M. J. Franklin, D. A. Patterson, and S. Perlmutter. ["Kira: Processing astronomy imagery using big data technology."](https://ieeexplore.ieee.org/abstract/document/7549106/) IEEE Transactions on Big Data (2016).
- [SIGMOD'15] F. A. Nothaft, M. Massie, T. Danford, Z. Zhang, U. Laserson, Carl Yeksigian, J. Kattalam, A. Ahuja, J. Hammerbacher, M. Linderman, M. J. Franklin, A. D. Joseph, D. A. Patterson. ["Rethinking Data-Intensive Science Using Scalable Analytics Systems."](https://dl.acm.org/citation.cfm?id=2742787)" In Proceedings of the 2015 ACM SIGMOD International Conference on Management of Data, pp. 631-646. ACM, 2015.
- [CIDR'15] D. Crankshaw, P. Bailis, J. E. Gonzalez, H. Li, Z. Zhang, M. J. Franklin, A. Ghodsi, M. I. Jordan. ["The Missing Piece in Complex Analytics: Low Latency."](https://arxiv.org/abs/1409.3809) Scalable Model Management and Serving with Velox, 7th Biennial Conference on Innovative Data Systems Research (CIDR), 2015.
- [eScience'14] Z. Zhang, and D. S. Katz. ["Using application skeletons to improve escience infrastructure."](https://ieeexplore.ieee.org/abstract/document/6972255/) In 2014 IEEE 10th International Conference on e-Science, vol. 1, pp. 111-118. IEEE, 2014.
- [SC'13] Z. Zhang, D. S. Katz, T. G. Armstrong, J. Wozniak, I. Foster. ["Parallelizing the Execution of Sequential Scripts."](https://dl.acm.org/citation.cfm?id=2503222) In Proceedings of the International Conference on High Performance Computing, Networking, Storage and Analysis, p. 31. ACM, 2013.
- [HPDC'13] Z. Zhang, D. S. Katz, M. Wilde, J. Wozniak, I. Foster. ["MTC Envelope: Defining the Capability of Large Scale Computers in the Context of Parallel Scripting Applications."](javascript:void(0)) In Proceedings of the 22nd international symposium on High-performance parallel and distributed computing, pp. 37-48. ACM, 2013.
- [IPDPS'13] T. Li, X. Zhou, K. Brandstatter, D. Zhao, K. Wang, A. Rajendran, Z. Zhang, I. Raicu. ["ZHT: A Light-weight Reliable Persistent Dynamic Scalable Zero-hop Distributed Hash Table."](https://ieeexplore.ieee.org/abstract/document/6569861/) In Parallel & distributed processing (IPDPS), 2013 IEEE 27th international symposium on, pp. 775-787. IEEE, 2013.
- [SC'12] Z. Zhang, D. S. Katz, J. Wozniak, A. Espinosa, I. Foster. ["Design and Analysis of Data Management in Scalable Parallel Scripting."](https://ieeexplore.ieee.org/abstract/document/6468455/) In Proceedings of the International Conference on High Performance Computing, Networking, Storage and Analysis, p. 85. IEEE, 2012.
- [CLUSTER'10] I. Raicu, I. Foster, M. Wilde, Z. Zhang, Y. Zhao, A. Szalay, P. Beckman, K. Iskra, P. Little, C. Moretti, A. Chaudhary, D. Thain. ["Middleware Support for Many-Task Computing."](https://link.springer.com/article/10.1007/s10586-010-0132-9) Cluster Computing 13, no. 3 (2010): 291-314.
- [Computer'09] M. Wilde, I. Foster, K. Iskra, P. Beckman, Z. Zhang, A. Espinosa, M. Hategan, B. Clifford, I. Raicu. ["Parallel Scripting for Applications at the Petascale and Beyond."](https://ieeexplore.ieee.org/abstract/document/5331905/) Parallel scripting for applications at the petascale and beyond." Computer 42, no. 11 (2009).
- [SC'08] Ioan Raicu, Zhao Zhang, Mike Wilde, Ian Foster, Pete Beckman, Kamil Iskra, Ben Clifford, ["Toward Loosely Coupled Programming on Petascale Systems."](https://ieeexplore.ieee.org/abstract/document/5219768/) In SC'08: Proceedings of the 2008 ACM/IEEE Conference on Supercomputing, pp. 1-12. IEEE, 2008.