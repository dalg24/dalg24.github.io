---
title: "Fast tree-based algorithms for DBSCAN for low-dimensional data on GPUs"
collection: publications
category: conferences
permalink: /publication/2023-09-13-paper-dbscan
excerpt: 'This paper is about fixing template issue #693.'
date: 2023-09-13
venue: "ICPP '23: Proceedings of the 52nd International Conference on Parallel Processing, Salt Lake City, Utah, USA"
paperurl: 'http://dalg24.github.io/files/2023-paper-icpp-dbscan.pdf'
citation: "Prokopenko A, Lebrun-Grandie D, Arndt A (2023). &quot;Fast tree-based algorithms for DBSCAN for low-dimensional data on GPUs.&quot; <i>ICPP '23: Proceedings of the 52nd International Conference on Parallel Processing</i>."
---

DOI Bookmark: [10.1145/3605573.3605594](https://doi.org/10.1145/3605573.3605594)

# Abstract:
DBSCAN is a well-known density-based clustering algorithm to discover arbitrary
shape clusters. While conceptually simple in serial, the algorithm is
challenging to efficiently parallelize on manycore GPU architectures. Common
pitfalls, such as asynchronous range query calls, result in high thread
execution divergence in many implementations. In this paper, we propose a new
framework for GPU-accelerated DBSCAN, and describe two tree-based algorithms
within that framework. Both algorithms fuse the search for neighbors with
updating cluster information, but differ in their treatment of dense regions of
the data. We show that the time taken to compute clusters is at most twice that
of determination of the neighbors. We compare the proposed algorithms with
existing CPU and GPU implementations, and demonstrate their competitiveness and
performance using a fast traversal structure (bounding volume hierarchy) for
low dimensional data. We also show that the memory usage can be reduced by
processing object neighbors dynamically without storing them.
