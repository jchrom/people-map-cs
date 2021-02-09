# Lidé na mapě

Mapa zobrazuje jména lidí, o kterých se píše na české Wikipedii. Co jméno, to článek, zahrnuto je dvě stě nejčtenějších, a to přímo Čechů, Čechoslováků, nebo lidí, které považujeme tak nějak za své.

Jména se objevují v místech, s nimiž jsou lidé nějakým způsobem spjati: buďto se tam narodili, nebo tam působili, zemřeli, mají tam památník a podobně. Čím větší jméno, tím čtenější stránka. Kliknutí na zelenou bublinu přivolá okénko s krátkou citací a odkazem na Wikipedii.

Veškerá data pocházejí přímo z Wikipedie, přesněji z [MediaWiki API](https://cs.wikipedia.org/w/api.php?action=help&modules=main&recursivesubmodules), [Wikimedia REST API](https://cs.wikipedia.org/api/rest_v1/) a [Wikidat](https://www.wikidata.org/wiki/Wikidata:Main_Page). Kód je psaný v Rku(https://cran.r-project.org/index.html). Mapa je kreslená v [MapBoxu](https://www.mapbox.com/). Data najdete v souboru [data.csv](../master/data.csv) včetně geolokačních údajů. Datový bod čtenosti představuje součet shlédnutí za jeden měsíc. V mapě je použit medián této hodnoty z posledních pěti let. Články mladší než jeden rok nejsou zahrnuty.
