---
layout: archive
title: "Papers"
permalink: /papers/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

======
Published
======
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Preprints
======
{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}