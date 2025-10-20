---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Dr. Noah Day is a post-doctoral resesarh fellow at the University of Melbourne. He completed his PhD at the University of Adelaide under the supervision of Dr. Luke Bennetts and Dr. Siobhan O’Farrell (CSIRO). Noah’s research explores how ocean waves interact with Antarctic sea ice, and how these processes influence the extent and behaviour of the ice, from short-term weather events to longer-term climate patterns.


# The Work I Do

### Figure from Unsupervised MIZ

![Unsupervised MIZ](http://noahday.github.io/images/figures/DayMIZ2024-Figure4.png){: style="width:600px;" }

### Figure from Cyclone

### Figure from Amp drop


# Publications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# Contact me

Noah Day
[noah.day@unimelb.edu.au](mailto:noah.day@unimelb.edu.au)