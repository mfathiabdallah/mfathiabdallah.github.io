---
layout: page
title: Publications
---

{% for publication in site.data.publications %}
<h2>{{ publication.title }}</h2>
<p>{{ publication.authors }}</p>
<p>{{ publication.venue }}</p>
<p>{{ publication.date }}</p>
<p><a href="{{ site.baseurl }}/pdfs/{{ publication.pdf }}">[Download PDF]</a></p>
{% endfor %}
