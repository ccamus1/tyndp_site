---
layout: pages
title: "Regions"
nav-breadcrumbs:
  - Regions: "/regions"
---
Regions are important blah blah blah

>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Odio nihil mollitia, eaque quisquam, fugiat id. Vitae eligendi repellendus ad consequatur, provident nemo doloribus voluptatum praesentium minima illum ratione cupiditate ab earum, maiores rem sequi perferendis iure debitis, suscipit consectetur adipisci inventore dolores quisquam! Dolorem tempore ab modi quia doloremque labore iusto quae mollitia, dolores incidunt. Similique saepe illo porro quis provident tenetur eaque praesentium. Illo consectetur quaerat, architecto reiciendis dolorem incidunt illum laborum accusamus possimus temporibus ut similique sed minus.

![]({{site.baseurl | append: "/assets/img/tyndp_map.png"}})

## Checkout your Region

<div class="row small-up-1 medium-up-2 large-up-3">
{% for i in (1..6)  %}
  <div class="column text-center">
    <a href="{{"/regions/test-region" | prepend: site.baseurl}}"><img src="//placehold.it/300x300" class="thumbnail" alt="">
    <div class="title">Baltics Region</div></a>
  </div>
{% endfor %}
</div>