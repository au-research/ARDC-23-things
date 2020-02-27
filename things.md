---
title: All the Research Data things
permalink: /researchdata/things/
---

{% for t in site.things %}
- [Thing {{t.thing}}:]({{site.baseurl}}/researchdata/thing-{{t.thing | prepend: '0' | slice: -2,2}}) {{t.title}}
  - {{t.description}}
  - {{t | inspect }} 
{% endfor %}
