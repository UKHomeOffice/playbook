---
layout : "page"
title: "User Centered Pages"
permalink: /usercenter/
---

# User Centered Page

{% for item in site.user-centereds %}
{% if item.title != page.title %}
<a href="{{item.url}}">{{forloop.index}}. {{item.title}}</a>
<br>
{% endif %}
{% endfor %}