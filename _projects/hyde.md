---
layout: page
title: "HyDe: Hyperspectral Denoising"
description: Hyperspectral Denoising algorithm toolbox in Python
img: assets/img/projects/hyde/10db-hyres-hyde.png
importance: 1
category: application
---

Image denoising is the task of recovering the true unknown image from a degraded observed image. It plays an important role in a variety of applications, for example in remote sensing imaging systems in lithological mapping. Hyperspectral Denoising is a Python toolbox aiming to provide, as the name suggests, denoising algorithms for hyperspectral image data. In particular, we provide:

* A wide variety of hyperspectral denoising algorithms (see Features for details)
* GPU acceleration for all algorithms
* An inuitive pythonic API design
* PyTorch compatibility

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/hyde/10db-noisy.png" title="hyde image" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
            Noisy HSI
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/hyde/10db-hyres-hyde.png" title="hyde image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/hyde/10db-hyres-matlab.png" title="hyde image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/hyde/10db-hyres-qrnn3d.png" title="hyde image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Image caption for all.
</div>

