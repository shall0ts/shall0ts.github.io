---
layout: page
title: OSU Athletics Ticket Analysis
description: an analysis of human behavior on college gamedays
img: assets/img/osu_stadium.jpg
importance: 1
category: school
related_publications: einstein1956investigations, einstein1950meaning
---

Refer to my <a href="https://github.com/shall0ts/Projects">GitHub</a> repository for the hardcopy of the PowerPoint presented to the Athletic Department and CSV files used for the analysis. 

This project was completed as part of the Industry Immersion program with a group of three other students in the class. Data was provided by OSU Athletics detailing all ticket scans on every Ohio State gameday in the 2022 college football season. 

Flash back to September 11th, 2021 and the first game of the season is at home against the Oregon Ducks. A reminder: Ohio State had no fans for all of the 2020 season due to COVID. People are excited for the first home game, but they are even more excited when the last game they could have even gone to was over 2 years ago. In addition, Ohio State is also using a new system to read tickets. Instead of barcode scanners, new near-field communcation devices were used to admit digital tickets. Unfortunaly, these scanners broke down, and in the name of safety, gate agents let everyone in. What was a large safety issue and possible entrance of non-ticketed fans caused OSU to take a closer look at how fans decide what gate to enter and the distribution of fans throughout all the gates. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/students.jpg" title="Student Rush" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Chaos ensues as gate agents attempt to hold back students, many here for their first gameday. 
</div>

Our analysis looked at the overall distribution of fans and which gates they decided to go into. We used a caluclated metric, Entires per Seat, to understand which gates were overcrowed. To explain: Each gate number corresponds to the same section number in the stadium. Fans are instructed to enter at the gate in which their section is closest to. However, because of game day activites, parking lot locations, and press setups, fans overcrowd the north gates of the stadium. These phenomenons are depicted below. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/stadium_dist.jpg" title="stadium fan dis" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/eps.jpg" title="Earnings per Seat" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, which percentage of fans go where is shown with a map and a compass. On the right, we show some of the most overcrowded gates using the Earnings per Seat metric.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
