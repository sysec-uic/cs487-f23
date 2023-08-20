---
layout: home
title: Building Secure Computer Systems
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: UIC CS 487 Building Secure Computer Systems
---

# CS 487: Building Secure Computer Systems

### Welcome to CS 487: Building Secure Computer Systems at UIC!
<!--
The link to this webpage is [https://sysec-uic.github.io/cs487-f23](https://sysec-uic.github.io/cs487-f23).
-->

Use links at the left side of this page to access the main course resources (most were mentioned in the [Syllabus](https://sysec-uic.github.io/cs487-f23/syllabus/)).

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

{% for module in site.modules %}
{{ module }}
{% endfor %}
