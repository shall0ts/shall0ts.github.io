---
layout: page
title: OSU Athletics Ticket Analysis
description: an analysis of human behavior on college gamedays
img: assets/img/osu_stadium.jpg
importance: 1
category: school
related_publications: einstein1956investigations, einstein1950meaning
---

This project was completed as part of the <a href="https://fisher.osu.edu/undergraduate/leadership-engagement/experiential-learning/industry-immersion-program">Industry Immersion</a> program with a group of three other students in the class. Data was provided by OSU Athletics detailing all ticket scans on every Ohio State gameday in the 2022 college football season. 

Flash back to September 11th, 2021 and the first game of the season is at home against the Oregon Ducks. A reminder: Ohio State had no fans for all of the 2020 season due to COVID. People are excited for the first home game, but they are even more excited when the last game they could have even gone to was over 2 years ago. In addition, Ohio State is also using a new system to read tickets. Instead of barcode scanners, new near-field communication devices were used to admit digital tickets. Unfortunately, these scanners broke down, and in the name of safety, gate agents let everyone in. What was a large safety issue and possible entrance of non-ticketed fans caused OSU to take a closer look at how fans decide what gate to enter and the distribution of fans throughout all the gates.

What was a nightmare for the Athletics Department turned into some opportunities for improvement! 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/students.jpg" title="Student Rush" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Chaos ensues as gate agents attempt to hold back students, many here for their first gameday. 
</div>

Our analysis looked at the overall distribution of fans and which gates they decided to go into. We used a calculated metric, Entires per Seat, to understand which gates were overcrowded. To explain: Each gate number corresponds to the same section number in the stadium. Fans are instructed to enter at the gate in which their section is closest to. However, because of game day activities, parking lot locations, and press setups, fans overcrowd the north gates of the stadium. These phenomenons are depicted below. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/stadium_dist.jpg" title="stadium fan dis" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/eps.jpg" title="Entries per Seat" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, which percentage of fans go where is shown with a map and a compass. On the right, we show some of the most overcrowded gates using the Earnings per Seat metric.
</div>

Here is a more in-depth look at two problem sections and the "best" section to enter in the stadium. The slides describe how small the percentage of people who actually sit in the sections are. Looking at the best section, there is proof of a trend that entries per seat decreases as the percentage of people who actually sit in the section corresponding to that gate increases. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/sec7_9_11.jpg" title="Gates 7,9,11" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/sec12_14.jpg" title="Gates 12, 14" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/sec23_25.jpg" title="Gates 23, 25" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left: Gates 7, 9, 11. In the middle: Gates: 12, 14. On the right: Gates 23, 25.
</div>

We presented this project to a member of the OSU Athletic Department on April 18th, 2023. Our project was received well, and some of the slides I shared above were utilized in the athletic director's end of year presentation. 

Refer to my <a href="https://github.com/shall0ts/Projects">GitHub repo</a> for PowerPoint presented to the Athletic Department and CSV files used for the analysis. The presentation has some other interesting visuals and details our recommended actions that OSU should take.  
