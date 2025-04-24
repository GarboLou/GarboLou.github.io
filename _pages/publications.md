---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="https://scholar.google.com/citations?user=YSHtzMkAAAAJ&hl=en">my Google Scholar profile</a>.</u> <br />
"\*" marks equal authorship

{% include base_path %}

{% assign last_year = "" %}
{% for post in site.publications reversed %}
  {% include archive-single.html
     post=post
     base_path=site.baseurl | append: '/publications/'
     last_year=last_year %}
  {% assign last_year = post.date | date: "%Y" %}
{% endfor %}
