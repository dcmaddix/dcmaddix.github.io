---
title: "Temporal oscillations in the porous medium equation: why harmonic averaging itself is not to blame"
collection: talks
type: "Talk"
permalink: /talks/harmonic_avg
venue: "SIAM Conference on Mathematical and Computational Issues in the Geosciences 2017"
date: 2017-09-01
location: "Erlangen, Germany"
---

[PhD Thesis Research on finite-volume averaged-based methods for nonlinear porous media flow.](https://events.conventus.de/fileadmin/congress/media/siam2017/druckelemente/SIAM2017_Program.pdf)

## Abstract

Harmonic averaging of the coefficient, $k(p) = p^m, m ≥ 1$, has been blamed for nonphysical locking and lagging of pressure
solutions of the Porous Medium Equation, $p_t − ∇ · (k(p)∇p) = 0$, that occur for small $p$. This degenerate parabolic equation
has applications to plasma heat transfer, gas and groundwater flow. The numerical issues also manifest themselves in spurious temporal oscillations, even with none in space. Arithmetic averaging has been suggested as an alternative. We show that harmonic averaging is not solely to blame and that an improved choice of temporal and spatial discretizations can avoid these issues. The harmonic problems can be traced for standard numerical schemes to a local anti-diffusive term in the modified equation and so can be compensated for. A similar approach works for superslow diffusion, where $k(p) = \exp(−1/p)$.
A more extreme case, arising in foam models, is where $k(p)$ is a step function, e.g. $k(p) = 1$ if $p ≥ 0.5$ and 0 otherwise. For this model, both harmonic and arithmetic averaging result in artificial temporal oscillations. To resolve this, we propose a new type of averaging, incorporating the shock position that can be estimated effectively.
