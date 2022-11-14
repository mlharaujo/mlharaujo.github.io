---
layout: archive
title: ""
permalink: /publications/
author_profile: true

#Accepted for Publication
#======
#{% for post in site.accepted reversed %}
 # {% include archive-single.html %}
#{% endfor %}
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Published Papers
======
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Accepted for Publication
======
{% for post in site.accepted reversed %}
  {% include archive-single.html %}
{% endfor %}

Preprints
======
{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}

PhD Thesis
======
{% for post in site.thesis reversed %}
  {% include archive-single.html %}
{% endfor %}
