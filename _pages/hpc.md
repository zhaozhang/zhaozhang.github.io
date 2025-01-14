---
layout: archive
# title: "The HPC Reading List"
permalink: /hpc/
author_profile: true
---

{% include base_path %}


# HPC Reading List

### Interconnect
1. Scott, Steve, Dennis Abts, John Kim, and William J. Dally. ["The blackwidow high-radix clos network."](https://dl.acm.org/doi/abs/10.1145/1150019.1136488) ACM SIGARCH Computer Architecture News 34, no. 2 (2006): 16-28.
1. Leiserson, Charles E., Zahi S. Abuhamdeh, David C. Douglas, Carl R. Feynman, Mahesh N. Ganmukhi, Jeffrey V. Hill, Daniel Hillis et al. ["The network architecture of the Connection Machine CM-5."](https://dl.acm.org/doi/pdf/10.1145/140901.141883) In Proceedings of the fourth annual ACM symposium on Parallel algorithms and architectures, pp. 272-285. 1992.
1. Kim, John, Wiliam J. Dally, Steve Scott, and Dennis Abts. ["Technology-driven, highly-scalable dragonfly topology."](https://dl.acm.org/doi/abs/10.1145/1394608.1382129) ACM SIGARCH Computer Architecture News 36, no. 3 (2008): 77-88.
1. Adiga, Narasimha R., Matthias A. Blumrich, Dong Chen, Paul Coteus, Alan Gara, Mark E. Giampapa, Philip Heidelberger et al. ["Blue Gene/L torus interconnection network."](https://ieeexplore.ieee.org/abstract/document/5388784/) IBM Journal of Research and Development 49, no. 2.3 (2005): 265-276.

### Programming Model
1. Walker, D.W. and Dongarra, J.J., 1996. ["MPI: a standard message passing interface."](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=dee5a2f78422f9e4b0cce4d0c763442846eb8cb1) Supercomputer, 12, pp.56-68.
1. Zheng, Yili, Amir Kamil, Michael B. Driscoll, Hongzhang Shan, and Katherine Yelick. ["UPC++: a PGAS extension for C++."](https://ieeexplore.ieee.org/abstract/document/6877339/) In 2014 IEEE 28th international parallel and distributed processing symposium, pp. 1105-1114. IEEE, 2014.
1. Jiang, Weihang, Jiuxing Liu, Hyun-Wook Jin, Dhabaleswar K. Panda, William Gropp, and Rajeev Thakur. ["High performance MPI-2 one-sided communication over InfiniBand."](https://ieeexplore.ieee.org/abstract/document/1336648/) In IEEE International Symposium on Cluster Computing and the Grid, 2004. CCGrid 2004., pp. 531-538. IEEE, 2004.
1. Kale, Laxmikant V., and Sanjeev Krishnan. ["Charm++ a portable concurrent object oriented system based on c++."](https://dl.acm.org/doi/pdf/10.1145/165854.165874) In Proceedings of the eighth annual conference on Object-oriented programming systems, languages, and applications, pp. 91-108. 1993.

### Collective Communication
1. Thakur, Rajeev, Rolf Rabenseifner, and William Gropp. ["Optimization of collective communication operations in MPICH."](https://journals.sagepub.com/doi/abs/10.1177/1094342005051521) The International Journal of High Performance Computing Applications 19, no. 1 (2005): 49-66.
1. Chan, Ernie, Marcel Heimlich, Avi Purkayastha, and Robert Van De Geijn. ["Collective communication: theory, practice, and experience."](https://onlinelibrary.wiley.com/doi/abs/10.1002/cpe.1206) Concurrency and Computation: Practice and Experience 19, no. 13 (2007): 1749-1783.
1. Pješivac-Grbović, Jelena, Thara Angskun, George Bosilca, Graham E. Fagg, Edgar Gabriel, and Jack J. Dongarra. ["Performance analysis of MPI collective operations."](https://link.springer.com/article/10.1007/s10586-007-0012-0) Cluster Computing 10 (2007): 127-143.

### Math Library
1. Balay, Satish, Shrirang Abhyankar, Mark Adams, Jed Brown, Peter Brune, Kris Buschelman, Lisandro Dalcin et al. ["PETSc users manual."](https://ora.ox.ac.uk/objects/uuid:fa2b9e7c-1c58-429c-90fd-f780a3c3dc7d) (2019).
1. Agullo, Emmanuel, Jim Demmel, Jack Dongarra, Bilel Hadri, Jakub Kurzak, Julien Langou, Hatem Ltaief, Piotr Luszczek, and Stanimire Tomov. ["Numerical linear algebra on emerging architectures: The PLASMA and MAGMA projects."](https://iopscience.iop.org/article/10.1088/1742-6596/180/1/012037/meta) In Journal of Physics: Conference Series, vol. 180, no. 1, p. 012037. IOP Publishing, 2009.
1. Choi, Jaeyoung, Jack J. Dongarra, Roldan Pozo, and David W. Walker. ["ScaLAPACK: A scalable linear algebra library for distributed memory concurrent computers."](https://www.computer.org/csdl/proceedings-article/fmpc/1992/00234898/12OmNCctfdR) In The Fourth Symposium on the Frontiers of Massively Parallel Computation, pp. 120-121. IEEE Computer Society, 1992.
1. Dongarra, Jack J., Piotr Luszczek, and Antoine Petitet. ["The LINPACK benchmark: past, present and future."](https://onlinelibrary.wiley.com/doi/abs/10.1002/cpe.728) Concurrency and Computation: practice and experience 15, no. 9 (2003): 803-820.
1. Williams, Samuel, Leonid Oliker, Richard Vuduc, John Shalf, Katherine Yelick, and James Demmel. ["Optimization of sparse matrix-vector multiplication on emerging multicore platforms."](https://dl.acm.org/doi/abs/10.1145/1362622.1362674?casa_token=C73C7v3OFHsAAAAA:_p_s_uWe_Iu7Axl28fTPvB5we-xalDi3vlio0Ks2XrnfofeUq6bmU_PbzfzaiGLQRPzSzbovwRFQzg) In Proceedings of the 2007 ACM/IEEE Conference on Supercomputing, pp. 1-12. 2007.


### I/O and Storage
1. Thakur, Rajeev, William Gropp, and Ewing Lusk. ["On implementing MPI-IO portably and with high performance."](https://dl.acm.org/doi/abs/10.1145/301816.301826) In Proceedings of the sixth workshop on I/O in parallel and distributed systems, pp. 23-32. 1999.
1. Folk, Mike, Gerd Heber, Quincey Koziol, Elena Pourmal, and Dana Robinson. ["An overview of the HDF5 technology suite and its applications."](https://dl.acm.org/doi/abs/10.1145/1966895.1966900) In Proceedings of the EDBT/ICDT 2011 workshop on array databases, pp. 36-47. 2011.
1. Chen, Peter M., Edward K. Lee, Garth A. Gibson, Randy H. Katz, and David A. Patterson. ["RAID: High-performance, reliable secondary storage."](https://dl.acm.org/doi/abs/10.1145/176979.176981) ACM Computing Surveys (CSUR) 26, no. 2 (1994): 145-185.
1. Patil, Swapnil V., Garth A. Gibson, Sam Lang, and Milo Polte. ["GIGA+ scalable directories for shared file systems."](https://dl.acm.org/doi/abs/10.1145/1374596.1374604) In Proceedings of the 2nd international workshop on Petascale data storage: held in conjunction with Supercomputing'07, pp. 26-29. 2007.

### Performance Modeling
1. Gibbons, Phillip B. ["A more practical PRAM model."](https://dl.acm.org/doi/pdf/10.1145/72935.72953) In Proceedings of the first annual ACM symposium on Parallel algorithms and architectures, pp. 158-168. 1989.
1. Culler, David, Richard Karp, David Patterson, Abhijit Sahay, Klaus Erik Schauser, Eunice Santos, Ramesh Subramonian, and Thorsten Von Eicken. ["LogP: Towards a realistic model of parallel computation."](https://dl.acm.org/doi/abs/10.1145/155332.155333) In Proceedings of the fourth ACM SIGPLAN symposium on Principles and practice of parallel programming, pp. 1-12. 1993.
1. Valiant, Leslie G. ["A bridging model for multi-core computing."](https://www.sciencedirect.com/science/article/pii/S0022000010000966) Journal of Computer and System Sciences 77, no. 1 (2011): 154-166.
1. Williams, Samuel, Andrew Waterman, and David Patterson. ["Roofline: an insightful visual performance model for multicore architectures."](https://dl.acm.org/doi/abs/10.1145/1498765.1498785) Communications of the ACM 52, no. 4 (2009): 65-76.

### Applications
1. Solomonik, Edgar, and James Demmel. ["Communication-optimal parallel 2.5 D matrix multiplication and LU factorization algorithms."](https://link.springer.com/chapter/10.1007/978-3-642-23397-5_10) In European Conference on Parallel Processing, pp. 90-109. Berlin, Heidelberg: Springer Berlin Heidelberg, 2011.
1. Agarwal, Ramesh C., Susanne M. Balle, Fred G. Gustavson, Mahesh Joshi, and Prasad Palkar. ["A three-dimensional approach to parallel matrix multiplication."](https://ieeexplore.ieee.org/abstract/document/5389455/) IBM Journal of Research and Development 39, no. 5 (1995): 575-582.
1. Datta, Kaushik, Mark Murphy, Vasily Volkov, Samuel Williams, Jonathan Carter, Leonid Oliker, David Patterson, John Shalf, and Katherine Yelick. ["Stencil computation optimization and auto-tuning on state-of-the-art multicore architectures."](https://ieeexplore.ieee.org/abstract/document/5222004/?casa_token=2MwitXx67hkAAAAA:cMX0_k8bZN_IjS0u-_CCM1fx28inXXVl9FuX3ImqkQUZNWqgw8XEmSz7sx_6gCdP2Wc2-15B-OI) In SC'08: Proceedings of the 2008 ACM/IEEE conference on Supercomputing, pp. 1-12. IEEE, 2008.
1. Warren, Michael S., and John K. Salmon. ["Astrophysical N-body simulations using hierarchical tree data structures."](https://www.thesalmons.org/john/ftp/sc92.pdf) SC 92 (1992): 570-576.
1. Sengupta, Shubhabrata, Mark Harris, Yao Zhang, and John D. Owens. ["Scan primitives for GPU computing."](https://escholarship.org/uc/item/8051p6nd) (2007).
1. Buluç, Aydin, and Kamesh Madduri. ["Parallel breadth-first search on distributed memory systems."](https://dl.acm.org/doi/abs/10.1145/2063384.2063471?casa_token=1eobK6Ln8JkAAAAA:giiF6-F3fse6gIIwscVJWo69F9QRKBnIYE0LoJDZvNwuy6mN4r5TSUuqDh5X1K2D2lR53koScFhpKQ) In Proceedings of 2011 International Conference for High Performance Computing, Networking, Storage and Analysis, pp. 1-12. 2011.
1. Holst, Terry L. ["Supercomputer applications in computational fluid dynamics."](https://ieeexplore.ieee.org/abstract/document/74132/) In Supercomputing'88: Proceedings of the 1988 ACM/IEEE Conference on Supercomputing, Vol. II Science and Applications, pp. 51-60. IEEE, 1988.
1. Dubey, Abhimanyu, Abhinav Jauhri, Abhinav Pandey, Abhishek Kadian, Ahmad Al-Dahle, Aiesha Letman, Akhil Mathur et al. ["The llama 3 herd of models."](https://arxiv.org/abs/2407.21783) arXiv preprint arXiv:2407.21783 (2024).

