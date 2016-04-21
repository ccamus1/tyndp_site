---
layout: pages
title: "Test Region Page"
reports:
  - 2030 Pan-European Capacity Analysis
  - A push for Projects of Common Interest
  - Baltic synchronization
  - Data and expertise as key ingredients 
  - Engagement with all involved actors
  - Future system perspectives
  - Getting projects built
  - Nordic and Baltic sea - regional planning
  - North Seas - regional planning
  - North-South interconnections in Central-East and South-East Europe - regional planning
  - North-South interconnections in Western Europe - regional planning
  - System adequacy
  - Technology
  - Viability of Energy mix
---
<style>
    .region-info {border-right: 3px solid #444;margin-bottom: 1em;min-height: 120px;}
    .bleed-section {position: relative;}
    #filter-group a {
        margin-bottom: 1px;
        display: block;
    }
</style>
<div class="row">
<div class="badge-heading medium-8 columns region-info">
    <p>Blah blah blah explains what this region is about. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nesciunt iusto tempore veniam eum dignissimos aspernatur, nemo rem aliquam ratione officia, suscipit fugit voluptatum nostrum ex eaque recusandae distinctio, sequi neque.</p>
</div>
<div class="medium-4 columns">
    <h2>Baltic <br>Region</h2>
</div>
</div>

<div class="bleed-section">
    <div id='map'></div>
    <div class="pin-topright pad1 z10 filter-container">
    <nav id="filter-group" class="checkbox-pill pill lifted fill-darkgrey round">
        {% for  i in (1..4) %}
        <a href="" class="button">Secnario {{i}} - This is the renewables scenerio</a>
        {% endfor %}
        
    </nav>
    </div>
</div>

<script src='https://api.tiles.mapbox.com/mapbox-gl-js/v0.17.0/mapbox-gl.js'></script>
<link href='https://api.tiles.mapbox.com/mapbox-gl-js/v0.17.0/mapbox-gl.css' rel='stylesheet' />
<style>
    body { margin:0; padding:0; }
    #map { position:relative; top:0; bottom:0; width:100%; height:500px; }
    .pin-top, .pin-right, .pin-bottom, .pin-left, .pin-topleft, .pin-topright, .pin-bottomleft, .pin-bottomright {
    position: absolute;
}
.pin-topright {
    top: 0;
    right: 0;
}
.filter-container {
    right: 20px;
    top: 10px;
}
.z10 {
    z-index: 10;
}
</style>
<script type="text/javascript">

mapboxgl.accessToken = 'pk.eyJ1IjoiZW50c29lIiwiYSI6ImNpbWxxYXJocDAwMG53Ymx3N2JxNGhtZDYifQ.YjNgK9usqRNrzxWXnR152g';
var map = new mapboxgl.Map({
    container: 'map',
    style: 'mapbox://styles/mapbox/streets-v8',
    center: [19.982, 57.073],
    zoom: 5
});

map.scrollZoom.disable();
map.addControl(new mapboxgl.Navigation({position:'top-left'}))

map.on('load', function () {
map.addSource("tyndp", {
            "type": "geojson",
            "data": "/mergeddata.geojson"
            //"data": dummy
        });



map.addLayer({
    "id": "polys",
    "source": "tyndp",
    "type": "fill",
    "interactive": true,
    "paint": {
        "fill-color": "#444444",
        "fill-opacity": 0.5,
        "fill-outline-color": "#FFF"
    },
    "filter": [
            "==", "$type", "Polygon"
        ],
});
map.addLayer({
    "id": "polys-o",
    "source": "tyndp",
    "type": "line",
    "interactive": true,
    "paint": {
        "line-color": "#FFFFFF",
        "line-opacity": 0.5,
        "line-width": 2
    },
    "filter": [
            "==", "$type", "Polygon"
        ],
});

map.addLayer({
    "id": "lines",
    "source": "tyndp",
    "type": "line",
    "interactive": true,
    "paint": {
        "line-color": "#000",
        "line-opacity": 0.9,
        "line-width": 2
    },
    "filter": [
            "==", "$type", "LineString"
        ],
});

map.addLayer({
    "id": "points",
    "source": "tyndp",
    "type": "circle",
    "interactive": true,
    "paint": {
        "circle-color": "#444444" 
    },
    "filter": [
            "==", "$type", "Point"
        ],
});

});

</script>

{% for i in page.reports %}
<section id="{{include.section_id}}" data-magellan-target="{{include.section_id}}" class="section {% cycle '', 'fill-grey' %}">
    <div class="row">
        <div class="medium-8 small-centered columns">
        <h2 class="text-center">{{i}}</h2>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Labore porro fuga quibusdam molestias, libero quo soluta sint omnis eaque pariatur obcaecati ipsa optio maxime corrupti maiores! Temporibus, corporis, consequatur. Porro.
        </div>
    </div>
</section>
{% endfor %}
