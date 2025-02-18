---
title: "Application Experiences on a GPU-Accelerated Arm-based HPC Testbed"
collection: publications
category: conferences
permalink: /publication/2023-02-27-paper-experiences-gpu-acclerated-arm-based-hpc-testbed
excerpt: 'This paper is about fixing template issue #693.'
date: 2023-02-27
venue: 'Proceedings of the HPC Asia 2023 Workshops'
paperurl: 'http://dalg24.github.io/files/2023-paper-hpc-asia-experiences-gpu-acclerated-arm-based-hpc-testbed.pdf'
citation: 'Elwasif et al. (2023). &quot;Application Experiences on a GPU-Accelerated Arm-based HPC Testbed.&quot; <i>Proceedings of the HPC Asia 2023 Workshops</i>.'
---

DOI Bookmark: [10.1145/3581576.3581621](https://doi.org/10.1145/3581576.3581621)

# Abstract:
This paper assesses and reports the experience of ten teams working to port,
validate, and benchmark several High Performance Computing applications on a
novel GPU-accelerated Arm testbed system. The testbed consists of eight NVIDIA
Arm HPC Developer Kit systems, each one equipped with a server-class Arm CPU
from Ampere Computing and two data center GPUs from NVIDIA Corp. The systems
are connected together using InfiniBand interconnect. The selected applications
and mini-apps are written using several programming languages and use multiple
accelerator-based programming models for GPUs such as CUDA, OpenACC, and OpenMP
offloading. Working on application porting requires a robust and easy-to-access
programming environment, including a variety of compilers and optimized
scientific libraries. The goal of this work is to evaluate platform readiness
and assess the effort required from developers to deploy well-established
scientific workloads on current and future generation Arm-based GPU-accelerated
HPC systems. The reported case studies demonstrate that the current level of
maturity and diversity of software and tools is already adequate for
large-scale production deployments.
