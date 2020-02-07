---
layout: article
title: Ancestry
date: February 6, 2020
lastEdit: February 7, 2020
sitemap:
  changeFrequency: 'daily'
---

As a player, you may choose one of a variety of ancestries in Uatera.

<ul>
  {% for ancestry in site.uatera_ancestries %}
    <li>
      <a href="{{ancestry.url}}">{{ ancestry.title }}</a> - {{ ancestry.subtitle }}
    </li>
  {% endfor %}
</ul>
