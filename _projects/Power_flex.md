---
layout: page
title: "Power System Flexibility"
permalink: /projects/energy-system-flexibility
description: ""
tags: [Energy Flexibility, Renewable Energy, Electricity Storage, ESOI, Optimization]
status: "Under construction"
img: assets/img/power_flex.webp
importance: 2
category: Research themes
---

<img src="/assets/img/power_flex.webp" alt="Power System Flexibility" style="width: 100%; border-radius: 10px; box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1); margin-bottom: 10px;" />

<p style="text-align: right; font-size: 0.85em; color: gray;">
  Image Credits: William Potter / Shutterstock.com
</p>


<div style="background-color: #fff3cd; color: #856404; border: 2px solid #ffeeba; padding: 10px 20px; margin: 20px 0; border-radius: 5px; font-weight: bold; text-align: center; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
  🚧 This web page is still under construction 🚧
</div>

My research addresses **energy system flexibility** challenges posed by the intermittent nature of renewable energies (solar, wind). It employs optimization methodologies and techno-economic modeling.

The developed models help to understand optimal integration of storage technologies (e.g., Li-ion batteries, hydrogen, pumped hydro storage) to effectively match renewable energy supply with demand, considering regional climates and electricity demand patterns.

### Related Publications

- **Clerjon, A.**, Perdu, F. (2022).  
[**Matching intermittent electricity supply and demand with electricity storage – An optimization based on a time scale analysis**](https://doi.org/10.1016/j.energy.2021.122799). *Energy*, Vol. 241.

- **Clerjon, A.**, Perdu, F. (2019).  
[**Matching intermittency and electricity storage characteristics through time scale analysis: an energy return on investment comparison**](https://doi.org/10.1039/C8EE01940A). *Energy & Environmental Science*, Vol. 12.

- Duval, J., **Clerjon, A.**, Parmentier, P., Perdu, F. (2025).  
[**Optimal deployment of wind and solar electricity considering regional climates and demand patterns to minimize dispatchable supply**](https://cea.hal.science/cea-05141769). ECOS2025 Conference Proceedings, Paris.

- **Clerjon, A.** (2021).  
[**Analysis and modeling of the impacts of intermittent renewable energies on the French electricity system**](https://theses.hal.science/tel-03230033). PhD Thesis, Université Grenoble Alpes.


---

Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
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
