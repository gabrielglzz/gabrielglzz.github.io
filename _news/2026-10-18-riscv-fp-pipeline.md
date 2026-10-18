---
layout: post
title: "Pipeline FP RISC-V: an interactive simulator for teaching computer architecture"
description: Web simulator of an in-order RISC-V pipeline with multicycle floating-point units, based on Hennessy, Patterson & Kozyrakis (7th ed.). Cycle diagram, cycle-by-cycle mode, English and Spanish.
date: 2026-10-18
inline: false
related_posts: false
og_image: https://ggomezlo.es/assets/img/projects/riscv-fp-pipeline.png
---

I have released [**Pipeline FP RISC-V**](https://ggomezlo.es/riscv-fp-pipeline/), a free web simulator of an in-order RISC-V pipeline with multicycle floating-point units, following Chapter 3 and Appendix C of _Computer Architecture: A Quantitative Approach_ (7th edition) by Hennessy, Patterson and Kozyrakis.

It shows the full cycle diagram of a program, or lets you step through it cycle by cycle, highlighting RAW, structural and WAW stalls and branch freezes, along with cycles, CPI and stalls by type. It is available in English and Spanish, and runs directly in the browser.

{% include figure.liquid loading="eager" path="assets/img/projects/riscv-fp-pipeline.png" class="img-fluid rounded z-depth-1" alt="Pipeline FP RISC-V simulator showing results and a cycle diagram" %}

[**Try it here →**](https://ggomezlo.es/riscv-fp-pipeline/)
