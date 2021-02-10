# Lidé na mapě

Česky | [English](../master/README_EN.md)

[Mapa](https://jchrom.github.io/people-map-cs/index.html) zobrazuje jména lidí, o kterých se píše na české Wikipedii. Co jméno, to článek, zahrnuto je dvě stě nejčtenějších Čechů, Čechoslováků, nebo lidí, které považujeme za své.

Jména se objevují v místech, s nimiž jsou jejich nositelé nějakým způsobem spjati: buďto se tam narodili, nebo tam působili, zemřeli, mají tam památník a podobně. Čím větší jméno, tím čtenější stránka. Kliknutí na zelenou bublinu přivolá okénko s krátkou citací a odkazem na Wikipedii.

K přesměrování na interaktivní mapu klikněte na obrázek.

<p>
  <a href="https://jchrom.github.io/people-map-cs/index.html" title="Klikněte k přesměrování na interaktivní mapu">
    <img src="../master/map.png" alt="map" height="225px" width="auto" target="_blank" />
  </a>
</p>

### Použité metody

Veškerá data pocházejí z Wikipedie, přesněji [MediaWiki API](https://cs.wikipedia.org/w/api.php?action=help&modules=main&recursivesubmodules) (jména, text článků, geolokace), [Wikimedia REST API](https://cs.wikipedia.org/api/rest_v1/) (údaje o čtenosti) a [Wikidat](https://www.wikidata.org/wiki/Wikidata:Main_Page) (datové položky místního určení). Kód použitý při akvizici je psaný v [Rku](https://cran.r-project.org/index.html). Mapu vykresluje [MapBox](https://www.mapbox.com/). Soubor [data.csv](../master/data.csv) obsahuje vyčištěná data, včetně geolokačních údajů. Datový bod čtenosti představuje počet shlédnutí za jeden měsíc. V mapě je použit medián této hodnoty z posledních pěti let. Články mladší než jeden rok nejsou zahrnuty.
