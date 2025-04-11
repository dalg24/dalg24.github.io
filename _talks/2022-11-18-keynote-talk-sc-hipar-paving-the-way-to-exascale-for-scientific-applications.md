---
title: "Paving the way to exascale for scientific applications"
collection: talks
type: "Invited Talk"
permalink: /talks/2022-11-18-keynote-talk-sc-hipar-paving-the-way-to-exascale-for-scientific-applications
venue: "SC22: 3rd Workshop on Hierarchical Parallelism for Exascale Computing (HiPar)"
date: 2022-11-18
location: "Dallas, Texas, USA"
slidesurl: "files/2022-slides-hipar-paving-the-way-to-exascale-for-scientific-applications.pdf"
---

I gave the opening keynote at the 2022 IEEE/ACM International Workshop on
Hierarchical Parallelism for Exascale Computing, during
[SC22](https://sc22.supercomputing.org).

I discussed the limitations of current C++ standards for HPC, highlighting the
progress with `std::mdspan` that is in route for inclusion in C++23.  I showed
how current C++ parallel algorithms underutilize modern GPUs like the AMD
MI250X and advocated for hierarchical parallelism (similar to Kokkos) to expose
more parallelism.  Finally, I explored the gap between the C++ memory model and
hardware reality, showcasing how Kokkos, SYCL, and libcu++ extend
`std::atomic_ref` with memory scope concepts.

[Download slides](https://dalg24.github.io/files/files/2022-slides-hipar-paving-the-way-to-exascale-for-scientific-applications.pdf)
