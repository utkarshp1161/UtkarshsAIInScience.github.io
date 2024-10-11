---
layout: page
title: Estimating structure property relationship in microsocpy using bayesian optimization
description: Bayesian optimization
img: assets/img/hAE_2.png
importance: 1
category: fun
---

In microscopy we often want to measure strucure property relationship. But it can also lead to significant beam damage if sample is exposed a lot to the beam.
----> have a beam damage image  <--------------
Q. Can we get some estimate of the property over unknown region by measuring the property over few regions?

for this analysis lets choose this dataset with ground truth measurements at all the points:
--> HAADF, spectrum <-------

The relationship we want to learn is b/w the strucutre patch and the target property which is some scalar value corresponding to the spectrum which we refer to as a scalarizer
--> Scalarizer images <-----

the measure of success for us is mean square error b/e predicted value and the ground truth value we already have.

Lets formulate the problem more regorously:
Symbols: 
a) I refers to th HAADF image of size m*n
b) 
b) coords referes to total coordinates around which patches


Steps:
    a) Make dataset
    b) 





<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/hAE_2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Human in the loop automated experiments.
</div>
[Try the simulator on this link](https://tiny.utk.edu/hAE)
