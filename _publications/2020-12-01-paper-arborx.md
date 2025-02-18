---
title: "ArborX: A Performance Portable Geometric Search Library"
collection: publications
category: manuscripts
permalink: /publication/2020-12-01-paper-arborx
excerpt: 'This paper is about fixing template issue #693.'
date: 2020-12-08
venue: 'ACM Transactions on Mathematical Software (TOMS)'
paperurl: 'https://dalg24.github.io/files/2020-paper-toms-arborx.pdf'
citation: 'Lebrun-Grandie et al. (2020). &quot;ArborX: A Performance Portable Geometric Search Library.&quot; <i>ACM Transactions on Mathematical Software</i>. 47(1).'
---

DOI Bookmark: [10.1145/3412558](https://doi.org/10.1145/3412558)

# Abstract:
Searching for geometric objects that are close in space is a fundamental
component of many applications. The performance of search algorithms comes to
the forefront as the size of a problem increases both in terms of total object
count as well as in the total number of search queries performed. Scientific
applications requiring modern leadership-class supercomputers also pose an
additional requirement of performance portability, i.e., being able to
efficiently utilize a variety of hardware architectures. In this article, we
introduce a new open-source C++ search library, ArborX, which we have designed
for modern supercomputing architectures. We examine scalable search algorithms
with a focus on performance, including a highly efficient parallel bounding
volume hierarchy implementation, and propose a flexible interface making it
easy to integrate with existing applications. We demonstrate the performance
portability of ArborX on multi-core CPUs and GPUs and compare it to the
state-of-the-art libraries such as Boost.Geometry.Index and nanoflann.
