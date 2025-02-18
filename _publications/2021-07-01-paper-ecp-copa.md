---
title: "Enabling particle applications for exascale computing platforms"
collection: publications
category: manuscripts
permalink: /publication/2021-07-01-paper-ecp-copa
excerpt: 'This paper is about fixing template issue #693.'
date: 2021-07-01
venue: 'The International Journal of High Performance Computing Applications (IJHPCA)'
paperurl: 'https://dalg24.github.io/files/2021-paper-ijhpca-ecp-copa.pdf'
citation: 'Mniszewski SM, Belak J, et al. (2021). &quot;Enabling particle applications for exascale computing platforms.&quot; <i>The International Journal of High Performance Computing Applications</i>. 35(6).'
---

DOI Bookmark: [10.1177/1094342021102282](https://doi.org/10.1177/10943420211022829)

# Abstract:
The Exascale Computing Project (ECP) is invested in co-design to assure that
key applications are ready for exascale computing. Within ECP, the Co-design
Center for Particle Applications (CoPA) is addressing challenges faced by
particle-based applications across four “sub-motifs”: short-range
particle–particle interactions (e.g., those which often dominate molecular
dynamics (MD) and smoothed particle hydrodynamics (SPH) methods), long-range
particle–particle interactions (e.g., electrostatic MD and gravitational
N-body), particle-in-cell (PIC) methods, and linear-scaling electronic
structure and quantum molecular dynamics (QMD) algorithms. Our crosscutting
co-designed technologies fall into two categories: proxy applications (or
“apps”) and libraries. Proxy apps are vehicles used to evaluate the viability
of incorporating various types of algorithms, data structures, and
architecture-specific optimizations and the associated trade-offs; examples
include ExaMiniMD, CabanaMD, CabanaPIC, and ExaSP2. Libraries are modular
instantiations that multiple applications can utilize or be built upon; CoPA
has developed the Cabana particle library, PROGRESS/BML libraries for QMD, and
the SWFFT and fftMPI parallel FFT libraries. Success is measured by
identifiable “lessons learned” that are translated either directly into parent
production application codes or into libraries, with demonstrated performance
and/or productivity improvement. The libraries and their use in CoPA’s ECP
application partner codes are also addressed.
