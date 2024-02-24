---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Computational and Mathematical Engineering, Stanford University, 2018
* M.S. in Computational and Mathematical Engineering, Stanford University, 2015
* B.A. in Applied Mathematics, University of California, Berkeley, 2012

Work Experience
======
* March 2021 - Present: Senior Applied Scientist, AWS AI Labs, Amazon Web Services (AWS)
  * I am leading the DeepEarth research team to develop novel physics-constrained machine learning solutions for computational fluid dynamics (CFD) and earth science applications.
* September 2018 - March 2021: Applied Scientist II, AWS AI Labs, Amazon Web Services (AWS)
  * I worked on developing, implementing and researching novel probabilistic deep learning models for time series forecasting in the open-source package [GluonTS](https://github.com/awslabs/gluonts) and leading the productionalization effort of these algorithms for Amazon Forecast.
* March 2016 - June 2018: Research Associate, Stanford University
  * In my PhD research, I worked with Professor Gerritsen in developing accurate and stable methods, as well as computationally efficient algorithms, for modeling flow through porous media. These methods are designed to accurately represent the underlying physics, and remove numerical artifacts associated with current state-of-the-art finite volume discretizations.
  * Advisor: Professor Margot Gerritsen
* June 2017 - September 2017: Extreme-Scale Data Analytics Intern
  * I developed physics-constrained (structure preserving) reduced order models (ROMs) for computationally expensive high fidelity models in computational fluid dynamics. 
* June 2015 - September 2015: CUDA Software Engineer Intern, NVIDIA
  * I developed efficient parallel algorithms for sparse matrix vector multiplication (spmv) on the GPU for CUDA toolkit libraries, including [cuSPARSE](https://docs.nvidia.com/cuda/cusparse/) and [nvGRAPH](https://github.com/rapidsai/nvgraph/blob/main/Acknowledgements.md). I also worked on problems in graph analytics, including utilizing the spmv to accelerate the pagerank, maximum flow and single source shortest path algorithms.
* May 2012 - June 2015: Computational Researcher, Lawrence Berkeley National Laboratory (LBL)
  * I worked in the Computational Research Division under Professor James Sethian, applying multiphase flow algorithms using the Voronoi Implicit Interface Method (VIIM) to shape optimization problems.
  
Publications
======
  <ul>{% for post in site.publications reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed%}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Awards and Honors
======
* December 2020: Best Paper Award, Machine Learning in Public Health NeurIPS 2020 Workshop
  *  *AutoODE: Bridging Physics-based and Data-driven modeling for COVID-19 Forecasting*
* May 2018: ICME Outstanding Leadership Award
* May 2018: Senior Teaching Fellow
* May 2016: 2016 ICME Xpo Poster Presentation Award
  *  *Sparse Matrix Vector Multiplication Using the Merge Path* (NVIDIA Internship project)
* 2013-2016: 2013 National Science Foundation (NSF) Graduate Research Fellowship Program (GRFP)
* March 2013: 2012 – 2013 Outstanding Graduate Student Instructor Award, University of California, Berkeley
* May 2012: Percy Lionel Davis Award for Excellence in Mathematics
* Spring 2011: Junior Initiate to Phi Beta Kappa Honor Society
* Fall 2008 – Spring 2012: Dean’s List/Honors to Date in College of Letters and Sciences

Service and leadership
======
* 2024: Lead organizer, area chair and program chair of the [ICLR 2024 Workshop on AI4DifferentialEquations In Science](https://ai4diffeqtnsinsci.github.io/)
* 2023-Present: Reviewer, *International Conference on Learning Representations (ICLR)*
* 2023-Present: Reviewer, *SIAM Journal on Scientific Computing (SISC)*
* 2023: Presented at Daves Avenue Elementary School Science Fair on ["Mathematics in Science"](https://drive.google.com/file/d/168kDOQXnGrK811CB6NXhXUkPUiOxLc2j/view)
* 2022-Present: Reviewer, *Nature Machine Intelligence, AISTATS*
* 2021-Present: Reviewer, *Conference on Neural Information Processing Systems (NeurIPS)*
* 2019-Present: Reviewer, *International Conference on Machine Learning (ICML)*
* 2016-Present: Reviewer, *Journal of Computational Physics, Science Advances*
* 2013-Present: Technology, Engineering and Mathematical Sciences Judge
* Fall 2011: Panel Member for Letters & Science “Finding Your Way” Advising Program
