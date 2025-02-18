---
title: "Advances in ArborX to support exascale applications"
collection: publications
category: manuscripts
permalink: /publication/2024-11-08-paper-advances-in-arborx-to-support-exascale-applications
excerpt: 'This paper is about fixing template issue #693.'
date: 2024-11-08
venue: 'The International Journal of High Performance Computing Applications (IJHPCA)'
paperurl: 'https://dalg24.github.io/files/2021-paper-ijhpca-ecp-copa.pdf'
citation: 'Prokopenko A, Lebrun-Grandie D, et al. (2024). &quot;Advances in ArborX to support exascale applications.&quot; <i>The International Journal of High Performance Computing Applications</i>. 39(1).'
---

DOI Bookmark: [10.1177/10943420241298296](https://doi.org/10.1177/10943420241298296)

# Abstract:
ArborX is a performance portable geometric search library developed as part of
the Exascale Computing Project (ECP). In this paper, we explore a collaboration
between ArborX and a cosmological simulation code HACC. Large cosmological
simulations on exascale platforms encounter a bottleneck due to the in-situ
analysis requirements of halo finding, a problem of identifying dense clusters
of dark matter (halos). This problem is solved by using a density-based DBSCAN
clustering algorithm. With each MPI rank handling hundreds of millions of
particles, it is imperative for the DBSCAN implementation to be efficient. In
addition, the requirement to support exascale supercomputers from different
vendors necessitates performance portability of the algorithm. We describe how
this challenge problem guided ArborX development, and enhanced the performance
and the scope of the library. We explore the improvements in the basic
algorithms for the underlying search index to improve the performance, and
describe several implementations of DBSCAN in ArborX. Further, we report the
history of the changes in ArborX and their effect on the time to solve a
representative benchmark problem, as well as demonstrate the real world impact
on production end-to-end cosmology simulations.
