---
layout: default
---

## About

GNU/Linux User Group is an extracurricular club at [Tufts University](https://www.tufts.edu/) 
dedicated to all things GNU, Linux, BSD, etc. All are welcome, even if you don't use Linux!


## Events

{% for ev in site.posts limit: 5 %}

{% if ev.layout == "event" %}

[{{ev.title}}]({{ev.url | relative_url}}) - {{ev.evdate | date: "%b %d, %Y"}} @ {{ev.evlocation}}

{% endif %}

{% endfor %}

[All events](events.html)


## Blog

{% for ev in site.posts limit: 5 %}

{% if ev.layout == "blog" %}

[{{ev.title}}]({{ev.url | relative_url}}) - {{ev.date | date: "%b %d, %Y"}}

{% endif %}

{% endfor %}

[All blog posts](blog.html)


## Contact

Discord: [https://discord.gg/Q8hg3vQz4B](https://discord.gg/Q8hg3vQz4B)


<!-- ## Members -->
