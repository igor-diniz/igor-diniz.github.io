---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
another crazy person in love with technology, and who believes that with her help we can live much better. I am currently in the second year of the computer engineering graduation at FEUP and I am doing an internship at PPN Tecnologia, learning about SalesForce platform and SAS programming language.

<div class="row">
{% include about/skills.html title="My Hard Skills" source=site.data.programming-skills %}
{% include about/skills.html title="\n" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>