---
layout: page
title: OSU Green Space Analysis
description: a GIS analysis on campus green space over time (1980-2022)
img: assets/img/oval.jpg
importance: 2
category: school
related_publications:
---

This analysis was completed for the purpose of an undergraduate student government (USG) General Assembly initiative, requested by a member on the Environment and Sustainability Committee. Members of the committee were interested in having an overall look at campus green space per student and how it has changed over time with campus expansion and construction. In addition, Ohio State's growing <a href="https://www.nbc4i.com/news/local-news/ohio-state-university/where-ohio-states-3-3-billion-construction-projects-stand/">construction portfolio</a> was causing unrest within the committee, as a couple project were going to be built on field used by many OSU sports clubs. 

Because of the nature of this request, I had a lot of freedom in how I wanted to define both "green space" and the student count. Some green space might be part of the OSU campus, yet not be useable or accessible to enrolled students. For example, I eliminated most of the fields in the Agricultural campus and some smaller spaces that weren't useable (i.e. covered in bushes). I counted all enrolled undergraduate and graduate students, yet broke it down into off-campus students and on-campus. Students were also grouped into buckets based on if their classes were online or in-person. Students were also weighted based on an estimated percentage to try and determine the number of students who are actually using the green space daily.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/total_insights.jpg" title="Student Breakdown" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    All student and green space numbers, more to come on how the amount of green space was calculated. Note the calculations of weights in the tables, for example, I estimated than 95% of all on campus students taking in-person classes use green space daily.
</div>

To help conceptualize how 161/462 square feet per student actually is, I included some rough comparisons below. A one car garage is about 200 square feet, near the unweighted value of green space per student in 2022.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/comp_insights.jpg" title="Conceptualize" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Comparisons to a space better understood by a human are shown. 
</div>

The 1980 map of campus was obtained from a contact in the Department of Geography at OSU. Utilizing ArcGIS, I was able to get a rough estimate of green space in both 1980 and 2022. After elimination of unusable green space, I used the number in the final analysis. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1980.JPG" title="1980 Map" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/2022.JPG" title="2022 Map" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Maps of campus with barriers in blue highlighter. 1980 on the left, 2022 on the right. 
</div>

This project was presented at a USG General Assembly meeting on November 30th, 2022. The analysis was well received. Several members of the Assembly thanked me for the work and considered themselves well informed with the status of campus green space.

Refer to my <a href="https://github.com/shall0ts/Projects">GitHub repo</a> for PowerPoint presented to the Assembly and a pdf of some of the notes I took during a touchpoint with the Environment and Sustainability Committee.
