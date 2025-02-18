---
title: "A single-tree algorithm to compute the Euclidean minimum spanning tree on GPUs"
collection: publications
category: conferences
permalink: /publication/2023-01-13-paper-emst
excerpt: 'This paper is about fixing template issue #693.'
date: 2023-01-13
venue: "ICPP '22: Proceedings of the 51st International Conference on Parallel Processing, Bordeaux, France"
paperurl: 'http://dalg24.github.io/files/2023-paper-hpc-asia-experiences-gpu-acclerated-arm-based-hpc-testbed.pdf'
citation: "Prokopenko A, Sao P, Lebrun-Grandie D (2022). &quot;A single-tree algorithm to compute the Euclidean minimum spanning tree on GPUs.&quot; <i>ICPP '22: Proceedings of the 51st International Conference on Parallel Processing</i>."
---

DOI Bookmark: [10.1145/3545008.3546185](https://doi.org/10.1145/3545008.3546185)

# Abstract:
Computing the Euclidean minimum spanning tree (Emst) is a computationally
demanding step of many algorithms. While work-efficient serial and
multithreaded algorithms for computing Emst are known, designing an efficient
GPU algorithm is challenging due to a complex branching structure, data
dependencies, and load imbalances. In this paper, we propose a single-tree
Borůvka-based algorithm for computing Emst on GPUs. We use an efficient nearest
neighbor algorithm and reduce the number of the required distance calculations
by avoiding traversing subtrees with leaf nodes in the same component. The
developed algorithms are implemented in a performance portable way using
ArborX, an open-source geometric search library based on the Kokkos framework.
We evaluate the proposed algorithm on various 2D and 3D datasets, show and
compare it with the current state-of-the-art open-source CPU implementations.
We demonstrate 4-24 × speedup over the fastest multi-threaded implementation.
We prove the portability of our implementation by providing results on a
variety of hardware: AMD EPYC 7763, Nvidia A100 and AMD MI250X. We show
scalability of the implementation, computing Emst for 37 million 3D
cosmological dataset in under a 0.5 second on a single A100 Nvidia GPU.

