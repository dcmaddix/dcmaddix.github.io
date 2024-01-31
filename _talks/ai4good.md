---
title: "Physics-constrained Machine Learning for Earth and Sustainability Science"
collection: talks
type: "Talk"
permalink: /talks/ai4good
venue: "2nd AI for Good Webinar Series: AI for Earth and Sustainability Science"
date: 2024-01-31
location: "Virtual"
---

My talk on ["Physics-constrained Machine Learning for Earth and Sustainability Science"](https://www.youtube.com/watch?v=qflj9ZPL1vo) at the [2nd AI for Good Webinar Series for AI for Earth and Sustainability Science](https://aiforgood.itu.int/event/physics-constrained-machine-learning-for-scientific-computing/) covers our following four research works in various scientific disciplines from epidemiology to weather and climate:
  - [Bridging Physics-based and Data-driven modeling for Learning Dynamical Systems](http://proceedings.mlr.press/v144/wang21a/wang21a.pdf), L4DC, 2021.
  - [Learning Physical Models that Can Respect Conservation Laws](https://arxiv.org/pdf/2302.11002.pdf), Physica D: Nonlinear Phenomena, 2024, ICML, 2023.
  - [Guiding Continuous Operator Learning through Physics-based boundary constraints](https://www.amazon.science/publications/guiding-continuous-operator-learning-through-physics-based-boundary-constraints), ICLR, 2023.
  - [PreDiff: Precipitation Nowcasting with Latent Diffusion Models](https://arxiv.org/pdf/2307.10422.pdf), NeurIPS, 2023.

## Abstract
In this talk, we discuss the development of physically-constrained machine learning (ML) models that incorporate techniques from scientific computing for learning dynamical and physical systems with applications in epidemiology and fluid dynamics. We first study the lack of generalization of black-box deep learning models for ODEs with applications to COVID-19 forecasting and the need for incorporation of advanced numerical integration schemes. We then focus on learning a physical model that satisfies conservation laws which are ubiquitous in science and engineering problems ranging from heat transfer to fluid flow. Violation of these well-known physical laws can lead to nonphysical solutions. To address this issue, we propose a framework, which constrains a pre-trained black-box ML model to satisfy conservation by enforcing the integral form from finite volume methods. We provide a detailed analysis of our method on learning with the Generalized Porous Medium Equation (GPME), a widely-applicable parameterized family of PDEs that illustrates the qualitative properties of both easier and harder PDEs that is used in groundwater flow. Our model maintains probabilistic uncertainty quantification (UQ), and deals well with shocks and heteroscedasticities. As a result, it achieves superior predictive performance on downstream tasks, e.g., shock location detection. Lastly, we study how to hard-constrain Neural Operator solutions to PDEs to satisfy the physical constraint of boundary conditions on a wide range of problems including Burgers’ and the Navier-Stokes’ equations. Our model improves the accuracy at the boundary and better guides the learning process on the interior of the domain. In summary, we demonstrate that carefully and properly enforcing physical constraints using techniques from numerical analysis results in better model accuracy and generalization in scientific applications. 

