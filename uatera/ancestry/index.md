---
layout: article
title: Ancestry
date: February 6, 2020
lastEdit: February 7, 2020
sitemap:
  changeFrequency: 'daily'
---

As a player, you may choose one of a variety of ancestries in Uatera.
Many of these ancestries are native to the region, such as the snowy Abryans
and the scrappy Lulans.

<ul class="ancestry_info_block_list">
  {% for ancestry in site.uatera_ancestries %}
    <li class="ancestry_info_block">
      <a href="{{ancestry.url}}">
        <p class="ancestry_info_block_header"> {{ancestry.title}} </p>
        <div class="ancestry_info_block_subheader">
          <p class="ancestry_info_block_source"> Source: {{ancestry.info_block.source}} </p>
          <p class="ancestry_info_block_race"> Race: {{ancestry.info_block.race}} </p>
          <p class="ancestry_info_block_version"> Version: {{ancestry.version}} </p>
        </div>
        <p class="ancestry_info_block_description"> {{ancestry.info_block.description}} </p>
      </a>
    </li>
  {% endfor %}
</ul>
