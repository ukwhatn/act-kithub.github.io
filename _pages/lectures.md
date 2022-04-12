---
title: "勉強会"
author: KITHUB
permalink: /lectures
---

# 過去の勉強会資料

<ul>
    {% for page in site.pages reversed %}
        {% if page.dir == "/lectures/" %}
            <li><a href="{{page.url}}">{{page.title}}</a></li>
        {% endif %}
    {% endfor %}
</ul>

<br>
