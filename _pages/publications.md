---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my articles on [my Google Scholar profile]({{site.author.googlescholar}}).
{% endif %}

## As a PhD Student

{% include base_path %}

{% assign phd_pubs = site.publications | where: "category", "phd" | sort: "date" | reverse %}
{% for post in phd_pubs %}
  {% include archive-single.html %}
{% endfor %}

## As an NLP Researcher (Working)

{% assign work_pubs = site.publications | where: "category", "work" | sort: "date" | reverse %}
{% for post in work_pubs %}
  {% include archive-single.html %}
{% endfor %}

## As a Master's Student

{% assign ms_pubs = site.publications | where: "category", "master" | sort: "date" | reverse %}
{% for post in ms_pubs %}
  {% include archive-single.html %}
{% endfor %}

## As an Undergraduate Student

{% assign ug_pubs = site.publications | where: "category", "undergrad" | sort: "date" | reverse %}
{% for post in ug_pubs %}
  {% include archive-single.html %}
{% endfor %}
