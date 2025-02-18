---
title: "Experiences with implementing Kokkos’ SYCL backend"
collection: publications
category: conferences
permalink: /publication/2024-04-08-paper-kokkos-sycl-backend
excerpt: 'This paper is about fixing template issue #693.'
date: 2024-04-08
venue: "IWOCL '24: Proceedings of the 12th International Workshop on OpenCL and SYCL"
paperurl: 'http://dalg24.github.io/files/2024-paper-iwocl-experiences-with-implementing-kokkos-sycl-backend.pdf'
citation: "Arndt A, Lebrun-Grandie D, Trott C (2024). &quot;Experiences with implementing Kokkos’ SYCL backend.&quot; <i>IWOCL '24: Proceedings of the 12th International Workshop on OpenCL and SYCL</i>."
---

DOI Bookmark: [10.1145/3648115.3648118](https://doi.org/10.1145/3648115.3648118)

# Abstract:
With the recent diversification of the hardware landscape in the
high-performance computing community, performance-portability solutions are
becoming more and more important. One of the most popular choices is Kokkos. In
this paper, we describe how Kokkos maps to SYCL 2020, how SYCL had to evolve to
enable a full Kokkos implementation, and where we still rely on extensions
provided by Intel’s oneAPI implementation. Furthermore, we describe how
applications can use Kokkos and its ecosystem to already explore upcoming C++
features also when using the SYCL backend. Finally, we are providing some
performance benchmarks comparing native SYCL and Kokkos and also discuss
hierarchical parallelism in the SYCL 2020 interface.
