---
layout: page
title: Centipede-Inspired Robotics
description: pushing the limits of
img: assets/img/juntao_paper.gif
importance: 1
category: work
related_publications: true
---

Most robotics efforts nowadays go towards the development of extremely complex algorithms for enhancing locomotion on complex terrains, relying on the so-called computational intelligence. However, such algorithms are highly dependent on vision capabilities, which are often not available in cluttered, dark, narrow environments like search-and-rescue environments are. For this reason, in our lab, our objective is to take advantage of our robot's mechanical intelligence in order to perform complex locomotion tasks even just using open-loop control systems, which then coupled with simpler algorithms can achieve high-quality results on all terrains.

By definition, centipede robots are long and narrow. The first feature, combined with their spatial redundancy (multiple legs) allows for great stability on every terrain. The second feature allows them to reach environments that most other legged robot cannot. The addition of bio-inspired compliance, bio-inspired tactile sensing, clever closed-loop/learning-based control systems then allows to optimize their performances.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/outdoor.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/natural.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <video width="100%" controls>
            <source src="{{ '/assets/img/SI_High_Resulution_compressed.mp4' | relative_url }}" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
</div>

<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

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
