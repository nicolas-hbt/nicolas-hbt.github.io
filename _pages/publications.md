---
layout: archive
title: "Publications and Conference Talks"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="https://scholar.google.com/citations?user=nHtB06wAAAAJ">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<style>
  .bottom-one {margin-bottom: 1cm;}
  .bottom-two {margin-bottom: 3cm;}
</style>
