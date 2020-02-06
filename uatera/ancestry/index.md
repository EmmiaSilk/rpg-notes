---
layout: article
title: Ancestry
---

<p>
  This is a test
</p>

<ul>
  {% for ancestry in site.uatera_ancestries %}
    <li>
      <a href="{{ancestry.url}}">{{ ancestry.title }}</a>
    </li>
  {% endfor %}
</ul>
