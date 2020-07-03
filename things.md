---
title: All the Research Data things
permalink: /researchdata/things/
---
Anyone can do 23 (research data) things at any time. Do them all, do some, cherry-pick the things you need or want to know about. Do them on your own, or get together in a group and share the learning. The program is intended to be flexible, adaptable and fun!

Each of the 23 things offers a variety of learning opportunities with activities at three levels of complexity: 
* Getting started
* Learn more
* Challenge me

All resources used in the program are online and free to use.

The 23 things are designed to build knowledge as the program progresses, so if you’re new to the wonderful world of research data management, we suggest you start with things 1-3 and then decide where you want to go from there.

{% for t in site.things %}
- [Thing {{t.thing}}:]({{site.baseurl}}{{t.url}}) {{t.title}}
  - {{t.description}}
{% endfor %}
