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
* B.A. in Applied Mathematics, University of California, Berkeley, 2012
* M.S. in Computational and Mathematical Engineering, Stanford University, 2015
* Ph.D in Computational and Mathematical Engineering, Stanford University, 2018

Work experience
======
* March 2016 - June: Research Associate
  * Stanford University
  * DIn my PhD research, I worked with Professor Gerritsen in developing accurate and stable methods, as well as computationally efficient algorithms, for modeling flow through porous media. These methods are designed to accurately represent the underlying physics, and remove numerical artifacts associated with current state-of-the-art finite volume discretizations.
  * Supervisor: Professor Margot Gerritsen

* June 2015 - September 2015: CUDA Software Engineer
  * NVIDIA
  * Developed efficient parallel algorithms for sparse matrix vector multiplication (spmv) on the GPU for CUDA toolkit libraries, including cuSPARSE and nvGRAPH. Worked on problems in graph analytics, including utilizing the spmv to accelerate the pagerank, maximum flow and single source shortest path algorithms.

* May 2012 - June 2015: Computational Researcher
  * Lawrence Berkeley National Laboratory (LBL)
  * Worked in the Computational Research Division under Professor James Sethian, applying multiphase flow algorithms using the Voronoi Implicit Interface Method (VIIM) to shape optimization problems.
  

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
