# A People Map of Czechia

[Česky](../master/README.md) | English

Each name on [the map](https://jchrom.github.io/people-map-cs/index.html) represents a Wikipedia article about a person. Included are the top two hundred most viewed articles about Czechs, Czechoslovaks, or people connected to Czechia in some way.

The location of each name indicates a birthplace, a workplace, a place of death, a memorial site or other type of association with the person. The bigger the name, the more pageviews accumulated by the article. Click on the green bubble to display a popup with an extract and a link to Wikipedia.

To go to the map, click the image below.

<p>
  <a href="https://jchrom.github.io/people-map-cs/index.html" title="Click for redirect to the map">
    <img src="../master/map.png" alt="map" height="225px" width="auto" target="_blank" />
  </a>
</p>

### Methods

All data comes from Wikipedia, i.e. [MediaWiki API](https://cs.wikipedia.org/w/api.php?action=help&modules=main&recursivesubmodules), [Wikimedia REST API](https://cs.wikipedia.org/api/rest_v1/) and [Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page), and the code to extract it is written in [R](https://cran.r-project.org/index.html). Map is rendered by [MapBox](https://www.mapbox.com/). Tidy data can be found in [data.csv](../master/data.csv) including the coordinates used in the map. _Views_ represent the sum total of pageviews per month. In this map, a median value over the last five years is used. Articles with less than one year worth of data were dropped.
