---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

permalink: /researchdata/things/
title: All the Research Data things

---
{% for thing in site.things %}
- [Thing {{thing.thing}}:](/ARDC-23-things/researchdata/thing-{{thing.thing}}) {{thing.title}}
	- {{thing.description}}
{% endfor %}