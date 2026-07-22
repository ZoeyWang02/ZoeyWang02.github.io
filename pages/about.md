---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}**,<br>
possibly a corgi, most definitely not!  Either way there are really neat things I am up to!

{% include elements/button.html link="/assets/pdf/Zhongyin_Wang_MSIM_CV_en.pdf" text="Download CV" %}

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
