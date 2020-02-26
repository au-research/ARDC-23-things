---
title: All the Research Data things
permalink: /researchdata/things/
---
{% for thing in site.things %}
- [Thing {{thing.thing}}:]({{site.baseurl}}/thing-{{thing.thing | prepend: "0" | slice: -1,2 }}.md) {{thing.title}}
  - {{thing.description}}
{% endfor %}
