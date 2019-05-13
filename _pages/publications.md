---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Journal Publications:

Z O. Toups, Nick LaLone, Sultan A. Alharthi, Hitesh Nidhi Sharma, and Andrew M. Webb. 2019. Making Maps Available for Play: Analyzing the Design of Game Cartography Interfaces. ACM Transactions on Computer-Human Interaction (ToCHI). [In press]

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
