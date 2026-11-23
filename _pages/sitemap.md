---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

- [About]({{ '/' | relative_url }})
- [Publications]({{ '/publications/' | relative_url }})
- [CV]({{ '/cv/' | relative_url }})

## Papers

{% include base_path %}
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
