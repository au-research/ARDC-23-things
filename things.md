---
title: All the Research Data things
permalink: /researchdata/things/
---

{% for this_thing in site.things %}
  {% assign padded_thing = this_thing.thing | downcase | prepend: '000' | slice: -1,2 %}
- [Thing {{this_thing.thing}}:]({{site.baseurl}}/researchdata/thing-{{padded_thing}}) {{this_thing.title}}
  - {{this_thing.description}}
{% endfor %}
