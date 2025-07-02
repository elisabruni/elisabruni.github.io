---
layout: page
title: 4 per 1000
description: Reaching the 4‰ objective
img: assets/img/4per1000.jpeg
importance: 1
category: work
related_publications: true
---

The International <a href="https://4p1000.org/?lang=en">"4 per 1000"</a> Initiative was launched in 2021 to promote sustainable agricultural practices that enhance soil organic carbon stocks. During my PhD, I used soil carbon models to assess whether the initiative’s theoretical goal—a 4‰ annual increase in soil organic carbon stocks—was feasible at the European scale.

Main findinds from my PhD work can be found in a [series of publications](#image-gallery) and in my <a href="https://pastel.hal.science/tel-03650802/">PhD manuscript</a>, which is also summarized in this <a href="https://holisoils.eu/is-it-feasible-to-increase-soil-carbon-stocks-by-4-per-1000-per-year/">Holisoils blog post</a>.


<div id="image-gallery" class="row">
    <div class="col-lg-3 col-md-3 col-sm-12 mt-3">
        <a href="https://doi.org/10.5194/bg-18-3981-2021" target="_blank">
            <div class="ratio ratio-4x3">
                {% include figure.liquid loading="eager" path="assets/img/4p1000_Century.png" title="example image" class="img-fluid rounded" %}
            </div>
        </a>
    </div>
    <div class="col-lg-3 col-md-3 col-sm-12 mt-3">
        <a href="https://doi.org/10.3389/fenvs.2022.824724" target="_blank">
            <div class="ratio ratio-4x3">
                {% include figure.liquid loading="eager" path="assets/img/defining_targets.png" title="example image" class="img-fluid rounded" %}
            </div>
        </a>
    </div>
        <div class="col-lg-3 col-md-3 col-sm-12 mt-3">
        <a href="https://doi.org/10.1111/ejss.13330" target="_blank">
            <div class="ratio ratio-4x3">
                {% include figure.liquid loading="eager" path="assets/img/4per1000_mme.jpg" title="example image" class="img-fluid rounded" %}
            </div>
        </a>
    </div>
    <div class="col-lg-3 col-md-3 col-sm-12 mt-3">
        <a href="https://doi.org/10.1016/j.scitotenv.2024.176525" target="_blank">
            <div class="ratio ratio-4x3">
                {% include figure.liquid loading="eager" path="assets/img/EU_cropland.png" title="example image" class="img-fluid rounded" %}
            </div>
        </a>
    </div>
</div>


<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
