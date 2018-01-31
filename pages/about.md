---
layout: page
title: About
description: 做一个心中有数的人
keywords: Xuyang Dong, 董旭阳
comments: true
menu: 关于
permalink: /about/
---

Simplicity is the ultimate sophistication.

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
