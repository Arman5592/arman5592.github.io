---
layout: page
title: Matrix Block-multiplier (Verilog)
description: Description and synthesis of a block-multiplier for arbitrary-sized matrices
img: assets/img/multiplier.jpg
importance: 1
category: university
related_publications:
---

[Corresponding repository](https://github.com/Arman5592/Matrix-Block-Multiplier-Verilog)

A matrix-multiplier (as a simple accelerator) which uses block multiplication to increase parallelism. This design is built around a shared memory (FPGA's BRAM) which contains operands and the resulting matrix; Thus, matrices of any size can be multiplied (given that they fit inside the RAM and are multiplicable). The verilog description is meticulously examined with simulations, and a synthesis was also carried out (but my Spartan-6 couldn't fit the entire design 😔).

I also extended this design for a graduate SoC course. The result was a matrix ALU which was synthesized in an ASIC workflow, and I plan on sharing it as soon as possible.
