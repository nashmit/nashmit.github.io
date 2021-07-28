---
layout: post
title: Optimal Control
subtitle: Technical Report
cover-img: /assets/img/multipleShooting.png
<!--- cover-img: /assets/img/path.jpg --->
<!--- thumbnail-img: /assets/img/multipleShooting.png --->
<!--- cover-img: /assets/img/DP.png --->
<!--- share-img: /assets/img/path.jpg --->
katex: True
tags: [Applied math, Nonlinear optimization, Optimal control, CasADi]
published: true
---

The main scope of this practical is to expose the interfaces of
**IDAS/CVODES** integrators from the **SUNDIALS suite**
into **Matlab**. To this end, the implementation
provides the means to define a **dynamical system**, to compute
**forward integration** as well as **first and second order
sensitivity** in a **parallelized** way. All of these are done by
**automatically C/C++ code generation** of the **integrator** and of the
**sensitivity** by using a **high level language** to define a
**dynamical system** on top of **CasADi**, which closely resembles a
**symbolical framework** without having the corresponding disadvantages.

The **pdf** version of this report can be found here: [Report](https://github.com/nashmit/SUNDIALS2Matlab/blob/master/report/report.pdf).

Alongside this report, a complete implementation can be found here:
[SUNDIALS2Matlab](https://github.com/nashmit/SUNDIALS2Matlab).\
\
***Index Terms:*** **IDAS, CVODES, SUNDIALS suite, dynamical system,
forward integration, sensitivity, parallelization, code generation,
CasADi, symbolical framework.**
