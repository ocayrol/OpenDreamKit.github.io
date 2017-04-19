---
layout: slides_wp
title: "WorkPackage Report"
theme: white
transition: none
author: Michael Kohlhase
period: 1st reporting period
wp: 6
---

<section data-markdown data-separator="^---\n" data-separator-vertical="^--\n">
--
## Overview

From the Proposal: Data/Knowledge/Software-Bases

![the big picture](https://github.com/OpenDreamKit/OpenDreamKit/blob/master/Proposal/Pictures/TheBigPicture.jpg)
---
![integration schemata](https://github.com/OpenDreamKit/OpenDreamKit/blob/master/WP6/CICM2016/tikz/three-graphs.pdf)

## Deliverables

{% comment %}
The include bellow gets the finished deliverables of the work pakacge and put the list in "delivs"
{% endcomment %}

{% include deliverables_slides.html %}

{{ delivs | size }} deliverables were submitted.

{% for d in delivs %}
- {{ d }}
{% endfor %}

--
### {{ delivs[2] }}

some more info on this deliverable

--
### {{ delivs[3] }}

some more info on this deliverable

---
## Big Achievments

We have done many great things and written nice reports.

--
### Some more details

That was really great

--
### Also we did this

And so on...

---
## More to come

Still, we have so much work!

--
### We will do this

(we have to, so...)

--
### And also this



</section>

