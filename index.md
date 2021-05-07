---
title: "DAFoam: Discrete Adjoint with OpenFOAM for High-fidelity Gradient-based Optimization"
keywords: sample homepage
sidebar: mydoc_sidebar
permalink: index.html
summary:
---

[**Latest Announcements**](news.html)
<div class="tickerv-wrap"><ul>
  {% for post in site.posts limit:10 %}
  <li>{{ post.date | date: "%b %-d, %Y. " }} {{ post.title }}. <a href="{{ post.permalink }}">Details.</a> </li>
  {% endfor %}
</ul></div>

|

DAFoam develops an efficient discrete adjoint method to perform high-fidelity gradient-based design optimization with the [MACH-Aero](https://github.com/mdolab/MACH-Aero) framework. DAFoam has the following features:

- It uses a popular open-source package [OpenFOAM](https://www.openfoam.com) for multiphysics analysis.
- It implements an efficient discrete adjoint approach with competitive speed, scalability, accuracy, and compatibility.
- It allows rapid discrete adjoint development for any steady and unsteady OpenFOAM primal solvers with modifying only a few hundred lines of source codes.
- It supports design optimizations for a wide range of disciplines such as aerodynamics, heat transfer, solid mechanics, hydrodynamics, and radiation.

DAFoam is distributed using the [GPL-v3 license](https://www.gnu.org/licenses/gpl-3.0.en.html), and its source code is avaiable from [Github](https://github.com/mdolab/dafoam)

Download the [DAFoam image](mydoc_get_started_download_docker.html) and follow the rest of steps in **Get started** to run your first DAFoam optimization!

<div markdown="0" id="carousel" class="carousel slide" data-ride="carousel" data-interval="2000" data-pause="hover" >
    <!-- Menu -->
    <ol class="carousel-indicators">
        <li data-target="#carousel" data-slide-to="0" class="active"></li>
        <li data-target="#carousel" data-slide-to="1"></li>
        <li data-target="#carousel" data-slide-to="2"></li>
        <li data-target="#carousel" data-slide-to="3"></li>
        <li data-target="#carousel" data-slide-to="4"></li>
    </ol>

    <!-- Items -->
    <div class="carousel-inner" markdown="0">
        <div class="item active">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/DPW6Flow.png" alt="Slide 1" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/propeller_wakes.png" alt="Slide 2" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/Rotor67AeroStructCover.png" alt="Slide 3" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/UBendAeroThermal.png" alt="Slide 4" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/JBC_front_page.png" alt="Slide 5" />
        </div>    
    </div>
</div>


{% include links.html %}
