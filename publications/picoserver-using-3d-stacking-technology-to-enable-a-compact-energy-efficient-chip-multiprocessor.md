---
layout: page
permalink: /publications/picoserver-using-3d-stacking-technology-to-enable-a-compact-energy-efficient-chip-multiprocessor/
---

Software Engineering

### Picoserver: using 3d stacking technology to enable a compact energy efficient chip multiprocessor
T. Kgil, S. D'Souza, A. Saidi, N. Binkert, R. Dreslinski, T. Mudge, S. Reinhardt, and K. Flautner
 
#### [Paper](https://citeseerx.ist.psu.edu/document?doi=e0ab822e29389631faf8331b850ae50120789334)
In Proceedings of the 12th International Conference on Architectural Support for Programming Languages and Operating Systems - ASPLOS, pages 117–128, 2006
 
#### Abstract

In this paper, we show how 3D stacking technology can be used to implement a simple, low-power, high-performance chip multiprocessor suitable for throughput processing. Our proposed architecture, PicoServer, employs 3D technology to bond one die containing several simple slow processing cores to multiple DRAM dies sufficient for a primary memory. The 3D technology also enables wide low-latency buses between processors and memory. These remove the need for an L2 cache allowing its area to be re-allocated to additional simple cores. The additional cores allow the clock frequency to be lowered without impairing throughput. Lower clock frequency in turn reduces power and means that thermal constraints, a concern with 3D stacking, are easily satisfied.

The PicoServer architecture specifically targets Tier 1 server applications, which exhibit a high degree of thread level parallelism. An architecture targeted to efficient throughput is ideal for this application domain. We find for a similar logic die area, a 12 CPU system with 3D stacking and no L2 cache outperforms an 8 CPU system with a large on-chip L2 cache by about 14% while consuming 55% less power. In addition, we show that a PicoServer performs comparably to a Pentium 4-like class machine while consuming only about 1/10 of the power, even when conservative assumptions are made about the power consumption of the PicoServer.


