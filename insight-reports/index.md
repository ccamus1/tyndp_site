---
layout: pages
title: "Insight Reports"
reports:
- name: 2030 Pan-European Capacity Analysis
- name: A push for Projects of Common Interest
- name: Baltic synchronization
- name: Data and expertise as key ingredients 
- name: Engagement with all involved actors
- name: Future system perspectives
- name: Getting projects built
- name: Nordic and Baltic sea - regional planning
- name: North Seas - regional planning
  link: "/insight-reports/nordic-baltic-sea/"
- name: North-South interconnections in Central-East and South-East Europe - regional planning
- name: North-South interconnections in Western Europe - regional planning
- name: System adequacy
- name: Technology
- name: Viability of Energy mix
bumf: >
  Lorem ipsum dolor sit amet, consectetur adipisicing elit. A alias ea aspernatur eaque veniam. Saepe rerum dolorum numquam quisquam animi perferendis fuga! Adipisci molestiae dicta, enim molestias voluptatum et alias corrupti autem perspiciatis libero provident ea assumenda, fugiat recusandae reprehenderit excepturi dolorem. Nemo sint aut ex hic illo unde labore sed magnam itaque deserunt blanditiis, eum, magni laudantium aliquam assumenda, cumque, accusamus architecto provident nam earum eos mollitia laboriosam dolor! Totam numquam nam animi omnis.
nav_tier1_active: "insight-reports"
nav-breadcrumbs:
  - Insight Reports: "/insight-reports"
---

{% for i in page.reports %}
<div id="{{include.section_id}}" data-magellan-target="{{include.section_id}}" class="section {% cycle '', 'fill-grey' %}">
    <div class="row">
        <div class="medium-8 small-centered columns">
        {% if i.link %}
        <a href="{{ i.link | prepend: site.baseurl }}"><h2 class="text-center">{{i.name}}</h2></a>
        {% else %}
        <h2 class="text-center">{{i.name}}</h2>
        {% endif %}
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Labore porro fuga quibusdam molestias, libero quo soluta sint omnis eaque pariatur obcaecati ipsa optio maxime corrupti maiores! Temporibus, corporis, consequatur. Porro.
        </div>
    </div>
</div>
{% endfor %}
