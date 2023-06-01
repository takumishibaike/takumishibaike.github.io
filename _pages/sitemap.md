---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-M4ERCSD2MV"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-M4ERCSD2MV');
</script>

{% include base_path %}

{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %}
