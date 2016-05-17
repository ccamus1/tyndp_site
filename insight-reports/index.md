---
layout: pages
title: "Insight Reports"
reports:
- name: 2030 Pan-European Capacity Analysis
  link: "/insight-reports/capacity-analysis"
- name: A push for Projects of Common Interest
  link: "/insight-reports/common-projects"
- name: Baltic synchronization 
  link: "/insight-reports/baltic-synchronisation"
- name: Data and expertise as key ingredients 
  link: "/insight-reports/data-and-expertise"
- name: Engagement with all involved actors
  link: "/insight-reports/engagement"
- name: Future system perspectives
  link: "/insight-reports/future-system"
- name: Getting projects built
  link: "/insight-reports/getting-projects-built"
- name: Nordic and Baltic sea - regional planning
  link: "/insight-reports/nordic-baltic-sea"
- name: North Seas - regional planning
  link: "/insight-reports/north-seas"
- name: North-South interconnections in Central-East and South-East Europe - regional planning
  link: "/insight-reports/north-south-interconnection-cee-see"
- name: North-South interconnections in Western Europe - regional planning
  link: "/insight-reports/north-south-interconnection-western"
- name: System adequacy
  link: "/insight-reports/system-ad"
- name: Technology
  link: "/insight-reports/technology"
- name: Viability of Energy mix
  link: "/insight-reports/energy-mix"
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
