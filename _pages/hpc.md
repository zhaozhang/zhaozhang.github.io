---
layout: archive
# title: "The HPC Reading List"
permalink: /hpc/
author_profile: true
---

{% include base_path %}


# HPC Reading List

### Interconnect
- Scott, Steve, Dennis Abts, John Kim, and William J. Dally. ["The blackwidow high-radix clos network."](https://dl.acm.org/doi/abs/10.1145/1150019.1136488) ACM SIGARCH Computer Architecture News 34, no. 2 (2006): 16-28.
- Leiserson, Charles E., Zahi S. Abuhamdeh, David C. Douglas, Carl R. Feynman, Mahesh N. Ganmukhi, Jeffrey V. Hill, Daniel Hillis et al. ["The network architecture of the Connection Machine CM-5."](https://dl.acm.org/doi/pdf/10.1145/140901.141883) In Proceedings of the fourth annual ACM symposium on Parallel algorithms and architectures, pp. 272-285. 1992.
- Kim, John, Wiliam J. Dally, Steve Scott, and Dennis Abts. ["Technology-driven, highly-scalable dragonfly topology."](https://dl.acm.org/doi/abs/10.1145/1394608.1382129) ACM SIGARCH Computer Architecture News 36, no. 3 (2008): 77-88.
- Adiga, Narasimha R., Matthias A. Blumrich, Dong Chen, Paul Coteus, Alan Gara, Mark E. Giampapa, Philip Heidelberger et al. ["Blue Gene/L torus interconnection network."](https://ieeexplore.ieee.org/abstract/document/5388784/) IBM Journal of Research and Development 49, no. 2.3 (2005): 265-276.

### Programming Model
- Walker, D.W. and Dongarra, J.J., 1996. ["MPI: a standard message passing interface."](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=dee5a2f78422f9e4b0cce4d0c763442846eb8cb1) Supercomputer, 12, pp.56-68.
- Zheng, Yili, Amir Kamil, Michael B. Driscoll, Hongzhang Shan, and Katherine Yelick. ["UPC++: a PGAS extension for C++."](https://ieeexplore.ieee.org/abstract/document/6877339/) In 2014 IEEE 28th international parallel and distributed processing symposium, pp. 1105-1114. IEEE, 2014.
- Jiang, Weihang, Jiuxing Liu, Hyun-Wook Jin, Dhabaleswar K. Panda, William Gropp, and Rajeev Thakur. ["High performance MPI-2 one-sided communication over InfiniBand."](https://ieeexplore.ieee.org/abstract/document/1336648/) In IEEE International Symposium on Cluster Computing and the Grid, 2004. CCGrid 2004., pp. 531-538. IEEE, 2004.
- Kale, Laxmikant V., and Sanjeev Krishnan. ["Charm++ a portable concurrent object oriented system based on c++."](https://dl.acm.org/doi/pdf/10.1145/165854.165874) In Proceedings of the eighth annual conference on Object-oriented programming systems, languages, and applications, pp. 91-108. 1993.

### Collective Communication
- Thakur, Rajeev, Rolf Rabenseifner, and William Gropp. ["Optimization of collective communication operations in MPICH."](https://journals.sagepub.com/doi/abs/10.1177/1094342005051521) The International Journal of High Performance Computing Applications 19, no. 1 (2005): 49-66.
- Chan, Ernie, Marcel Heimlich, Avi Purkayastha, and Robert Van De Geijn. ["Collective communication: theory, practice, and experience."](https://onlinelibrary.wiley.com/doi/abs/10.1002/cpe.1206) Concurrency and Computation: Practice and Experience 19, no. 13 (2007): 1749-1783.
- Pješivac-Grbović, Jelena, Thara Angskun, George Bosilca, Graham E. Fagg, Edgar Gabriel, and Jack J. Dongarra. ["Performance analysis of MPI collective operations."](https://link.springer.com/article/10.1007/s10586-007-0012-0) Cluster Computing 10 (2007): 127-143.

### Math Library
- Balay, Satish, Shrirang Abhyankar, Mark Adams, Jed Brown, Peter Brune, Kris Buschelman, Lisandro Dalcin et al. ["PETSc users manual."](https://ora.ox.ac.uk/objects/uuid:fa2b9e7c-1c58-429c-90fd-f780a3c3dc7d) (2019).
- Agullo, Emmanuel, Jim Demmel, Jack Dongarra, Bilel Hadri, Jakub Kurzak, Julien Langou, Hatem Ltaief, Piotr Luszczek, and Stanimire Tomov. ["Numerical linear algebra on emerging architectures: The PLASMA and MAGMA projects."](https://iopscience.iop.org/article/10.1088/1742-6596/180/1/012037/meta) In Journal of Physics: Conference Series, vol. 180, no. 1, p. 012037. IOP Publishing, 2009.
- Choi, Jaeyoung, Jack J. Dongarra, Roldan Pozo, and David W. Walker. ["ScaLAPACK: A scalable linear algebra library for distributed memory concurrent computers."](https://www.computer.org/csdl/proceedings-article/fmpc/1992/00234898/12OmNCctfdR) In The Fourth Symposium on the Frontiers of Massively Parallel Computation, pp. 120-121. IEEE Computer Society, 1992.
- Dongarra, Jack J., Piotr Luszczek, and Antoine Petitet. ["The LINPACK benchmark: past, present and future."](https://onlinelibrary.wiley.com/doi/abs/10.1002/cpe.728) Concurrency and Computation: practice and experience 15, no. 9 (2003): 803-820.


### I/O and Storage
- Thakur, Rajeev, William Gropp, and Ewing Lusk. ["On implementing MPI-IO portably and with high performance."](https://dl.acm.org/doi/abs/10.1145/301816.301826) In Proceedings of the sixth workshop on I/O in parallel and distributed systems, pp. 23-32. 1999.
- Folk, Mike, Gerd Heber, Quincey Koziol, Elena Pourmal, and Dana Robinson. ["An overview of the HDF5 technology suite and its applications."](https://dl.acm.org/doi/abs/10.1145/1966895.1966900) In Proceedings of the EDBT/ICDT 2011 workshop on array databases, pp. 36-47. 2011.
- Chen, Peter M., Edward K. Lee, Garth A. Gibson, Randy H. Katz, and David A. Patterson. ["RAID: High-performance, reliable secondary storage."](https://dl.acm.org/doi/abs/10.1145/176979.176981) ACM Computing Surveys (CSUR) 26, no. 2 (1994): 145-185.
- Patil, Swapnil V., Garth A. Gibson, Sam Lang, and Milo Polte. ["GIGA+ scalable directories for shared file systems."](https://dl.acm.org/doi/abs/10.1145/1374596.1374604) In Proceedings of the 2nd international workshop on Petascale data storage: held in conjunction with Supercomputing'07, pp. 26-29. 2007.

### Applications