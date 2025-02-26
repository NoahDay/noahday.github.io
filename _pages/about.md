---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD candidate studying the influence of ocean surface waves on the evolution of Antarctic sea ice. My research combines numerical modeling and statistical analysis to improve our understanding of wave–ice interactions and their impact on polar climate systems.


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
[noah.day@adelaide.edu.au](mailto:noah.day@adelaide.edu.au)