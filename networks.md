---
title: Community Networks
layout: default
---
## Community Network Projects
[Our _Stable_ Networks presentation](https://cryptpad.fr/slide/#/2/slide/view/Q7uOjmo75Ua4R+L5Scjug9doHfl52XGMdRu2frmTWQk/)  

A list of <span class='forming'>forming</span>, <span class='active'>active</span> or <span class='inactive'>inactive</span> community-run networks. Want to add a network? [Edit the list](https://github.com/buildyourowninternet/buildyourowninternet.github.io/edit/master/_data/networks.csv) or tweet info using #buildyourowninternet. 

From [networks.csv](https://github.com/buildyourowninternet/buildyourowninternet.github.io/blob/master/_data/networks.csv) in no particular order:

<ul>
{% for network in site.data.networks %}
  <li class="{{ network.status }}"><a href="{{ network.url }}" target="_blank">{{ network.name }}</a> @ <a href="{{ network.localeId }}" target="_blank">{{ network.locale }}</a></li>
{% endfor %}
</ul>

Information about community networks was gathered from various sources including <https://en.wikipedia.org/wiki/List_of_wireless_community_networks_by_region> , <https://www.metamesh.org/community-wifi-resources>, <http://battlemesh.org> and <https://sudoroom.org/wiki/Mesh/Other_mesh_projects> .

