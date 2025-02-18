---
title: "PANDORA: A Parallel Dendrogram Construction Algorithm for Single Linkage Clustering on GPU"
collection: publications
category: conferences
permalink: /publication/2024-08-12-paper-parallel-dendogram-construction
excerpt: 'This paper is about fixing template issue #693.'
date: 2023-09-13
venue: "ICPP '24: Proceedings of the 53rd International Conference on Parallel Processing, Gotland, Sweden"
paperurl: 'http://dalg24.github.io/files/2024-paper-icpp-parallel-dendogram-construction.pdf'
citation: "Sao P, Prokopenko A, Lebrun-Grandie D (2024). &quot;PANDORA: A Parallel Dendrogram Construction Algorithm for Single Linkage Clustering on GPU.&quot; <i>ICPP '24: Proceedings of the 53rd International Conference on Parallel Processing</i>."
---

DOI Bookmark: [10.1145/3673038.3673148](https://doi.org/10.1145/3673038.3673148)

# Abstract:
This paper introduces Pandora, a parallel algorithm for computing dendrograms,
the hierarchical cluster trees for single linkage clustering (SLC). Current
parallel approaches construct dendrograms by partitioning a minimum spanning
tree and removing edges. However, they struggle with skewed,
hard-to-parallelize real-world dendrograms. Consequently, computing dendrograms
is the sequential bottleneck in HDBSCAN*[21], a popular SLC variant.

Pandora uses recursive tree contraction to address this limitation. Pandora
contracts nodes to construct progressively smaller trees. It computes the
smallest contracted dendrogram and expands it by inserting contracted edges.
This recursive strategy is highly parallel, skew-independent, work-optimal, and
well-suited for GPUs and multicores.

We develop a performance portable implementation of Pandora in Kokkos[31] and
evaluate its performance on multicore CPUs and multi-vendor GPUs (e.g., Nvidia,
AMD) for dendrogram construction in HDBSCAN*. Multithreaded Pandora is 2.2x
faster than the current best-multithreaded implementation. Our GPU version
achieves 6-20x speedup on AMD GPUs and 10-37x on NVIDIA GPUs over multithreaded
Pandora. Pandora removes HDBSCAN*’s sequential bottleneck, greatly boosting
efficiency, particularly with GPUs.
