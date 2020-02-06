---
layout: article
title: Ancestry
---

As a player, you may choose one of a variety of ancestries in Uatera.

<ul>
  {% for ancestry in site.uatera_ancestries %}
    <li>
      <a href="{{ancestry.url}}">{{ ancestry.title }}</a> - {{ ancestry.subtitle }}
    </li>
  {% endfor %}
</ul>
