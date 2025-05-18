---
title: "The Kokkos OpenMPTarget Backend: Implementation and Lessons Learned"
collection: publications
category: conferences
permalink: /publication/2023-09-01-paper-kokkos-openmptarget-backend
excerpt: 'This paper is about fixing template issue #693.'
date: 2023-09-01
venue: 'IWOMP 2023 : 19th International Workshop on OpenMP'
paperurl: 'http://dalg24.github.io/files/2023-paper-iwomp-kokkos-openmptarget-backend-implementation-and-lessons-learned.pdf'
citation: 'Gayatri et al. (2023). &quot;The Kokkos OpenMPTarget Backend: Implementation and Lessons Learned.&quot; <i>IWOMP 2023 : 19th International Workshop on OpenMP</i>.'
---

DOI Bookmark: [10.1007/978-3-031-40744-4_7](https://www.doi.org/10.1007/978-3-031-40744-4_7)

# Abstract:
As the supercomputing landscape diversifies, solutions such as Kokkos to write
vendor agnostic applications and libraries have risen in popularity. Kokkos
provides a programming model designed for performance portability, which allows
developers to write a single source implementation that can run efficiently on
various architectures. At its heart, Kokkos maps parallel algorithms to
architecture and vendor specific backends written in lower level programming
models such as CUDA and HIP. Another approach to writing vendor agnostic
parallel code is using OpenMP’s directives based approach, which lets
developers annotate code to express parallelism. It is implemented at the
compiler level and is supported by all major high performance computing
vendors, as well as the primary Open Source toolchains GNU and LLVM. Since its
inception, Kokkos has used OpenMP to parallelize on CPU architectures. In this
paper, we explore leveraging OpenMP for a GPU backend and discuss the
challenges we encountered when mapping the Kokkos APIs and semantics to OpenMP
target constructs. As an exemplar workload we chose a simple conjugate gradient
solver for sparse matrices. We find that performance on NVIDIA and AMD GPUs
varies widely based on details of the implementation strategy and the chosen
compiler. Furthermore, the performance of the OpenMP implementations decreases
with increasing complexity of the investigated algorithms.
