# People map of Czechia

[Česky](../master/README.md) | English

The names on [the map](https://jchrom.github.io/people-map-cs/index.html) belong to people described in Czech Wikipedia, including the top two hundred most viewed articles. These are either Czech, Czechoslovak, or connected to Czechia in some way.

The location of each name indicates a connection between the place and the person: Birthplace, workplace, place of death, memorial site and similar. The bigger the name, the more pageviews accumulated by the article. Click on the green bubble to display a popup with an extract and a link to Wikipedia.

All data comes from Wikipedia, specifically [MediaWiki API](https://cs.wikipedia.org/w/api.php?action=help&modules=main&recursivesubmodules), [Wikimedia REST API](https://cs.wikipedia.org/api/rest_v1/) and [Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page), and the code to extract it is written in [R](https://cran.r-project.org/index.html). Map is rendered by [MapBox](https://www.mapbox.com/). Tidy data can be found in [data.csv](../master/data.csv) including the coordinates used in the map. Pageviews is a series of values, each of which represents the sum total of views per month. In this map, median value is used. Articles with less than one year worth of data were dropped.
