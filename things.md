---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
permalink: /researchdata/things/
title: All the Research Data things

---
{% for a_thing in site.things %}
- [Thing {{a_thing.thing}}](/researchdata/thing-{{a_thing.thing}}) - {{a_thing.title}}
	- {{a_thing.description}}
{% endfor %}

