---
layout: page
title: equivariant tensors and machine learning
description: with W. Gregory, N. Marshall, J. Tonelli-Cueto, and S. Villar
img: /assets/img/mnistnoise.png
importance: 1
category: work
---

In <a href="https://arxiv.org/abs/2106.06610">previous</a> <a href="https://arxiv.org/abs/2204.00887">work</a>, <a href="https://www.ams.jhu.edu/villar/">Soledad Villar</a> and collaborators took advantage of the symmetries present in physics in order to improve the application of machine learning. This project aims to build on that work to extend the applicability of their results.

Among the proposed directions in the project was an extension of previous results from vector-valued functions to tensor-valued functions, as one cannot express every function in physics as a vector function. We propose to continue work toward extending the results to equivariant functions of the form for several groups of relevance in physics, including the orthogonal and symplectic groups.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/illustris-cropped.png" title="stiefel sphere example" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
	The thumbnail image consists of MNIST digits corrupted by different types of noise. Our SparseVectorHunter method utilizing equivariant tensor functions recovers the original image better than existing methods.
</div>
