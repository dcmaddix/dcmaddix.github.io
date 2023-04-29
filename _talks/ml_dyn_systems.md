---
title: "Physics-constrained Machine Learning for Scientific Computing"
collection: talks
type: "Talk"
permalink: /talks/ml_and_dyn_sys
venue: "Machine Learning and Dynamical Systems Seminar, Alan Turing Institute"
date: 2023-04-13
location: "London, England"
---

My invited talk on ["Physics-constrained Machine Learning for Scientific Computing"](https://www.youtube.com/watch?v=ag5qEEYTNFg) at the [Machine Learning and Dynamical Systems Seminar](https://www.turing.ac.uk/research/interest-groups/machine-learning-and-dynamical-systems) at the Alan Turing Institute covers our following three research works:
  - [Bridging Physics-based and Data-driven modeling for Learning Dynamical Systems](http://proceedings.mlr.press/v144/wang21a/wang21a.pdf), L4DC, 2021.
  - [Learning Physical Models that Can Respect Conservation Laws](https://arxiv.org/pdf/2302.11002.pdf), ICML, 2023.
  - [Guiding Continuous Operator Learning through Physics-based boundary constraints](https://www.amazon.science/publications/guiding-continuous-operator-learning-through-physics-based-boundary-constraints), ICLR, 2023.

## Abstract
In this talk, we discuss the development of physically-constrained machine learning (ML) models that incorporate techniques from scientific computing for learning dynamical and physical systems with applications in epidemiology and fluid dynamics. We first study the lack of generalization of black-box deep learning models for ODEs with applications to COVID-19 forecasting and the need for incorporation of advanced numerical integration schemes. We then focus on learning a physical model that satisfies conservation laws which are ubiquitous in science and engineering problems ranging from heat transfer to fluid flow. Violation of these well-known physical laws can lead to nonphysical solutions. To address this issue, we propose a framework, which constrains a pre-trained black-box ML model to satisfy conservation by enforcing the integral form from finite volume methods. We provide a detailed analysis of our method on learning with the Generalized Porous Medium Equation (GPME), a widely-applicable parameterized family of PDEs that illustrates the qualitative properties of both easier and harder PDEs. Our model maintains probabilistic uncertainty quantification (UQ), and deals well with shocks and heteroscedasticities. As a result, it achieves superior predictive performance on downstream tasks, e.g., shock location detection. Lastly, we study how to hard-constrain Neural Operator solutions to PDEs to satisfy the physical constraint of boundary conditions on a wide range of problems including Burgers’ and the Navier-Stokes’ equations. Our model improves the accuracy at the boundary and better guides the learning process on the interior of the domain. In summary, we demonstrate that carefully and properly enforcing physical constraints using techniques from numerical analysis results in better model accuracy and generalization in scientific applications.
