# Onderzoekspunten NotS project
Het product is een “Cyber physical system” (CPS). Een CPS-systeem werkt samen met een “computer” die communiceert met de fysieke wereld. Het systeem levert en gebruikt data-toegang en data-processing diensten beschikbaar op het internet. In het kader van NotS word er geacht nieuwe technologie te gebruiken. Voor ons stofzuiger project staan enkele onderzoekpunten primair.

### Looproute algoritme
De stofzuiger moet door middel van optimale looproutes door het huishouden heen navigeren. Het *A\* Pathfinder 1* algoritme word in de praktijk veel gebruikt door zijn compleetheid, optimaliteit en efficiëntie. Voor het berekenen van looproutes worden *vertex grafieken 2* toegepast.

* 1 A\* Pathfinder bron: https://en.wikipedia.org/wiki/A*_search_algorithm*
* 2 In computer science, graph traversal refers to the process of visiting each vertex in a graph.*

### Object detectie
De robot mag natuurlijk niet tegen een object botsen. Het systeem moet dus uitgerust zijn met sensoren die objecten detecteren. Tevens zijn de sensoren vereist om de omgeving te mappen waar het looproute algoritme op los word gelaten. 

*Beacons zouden als oplossing kunnen dienen, maar worden handmatig aangebracht en dekken daarom niet de lading.*

### Locatie herkenning
De robot moet weten waar in de ruimte het bevindt. Voor dit probleem zijn verschillende oplossingen mogelijk. Bijvoorbeeld een camera aan het plafond die herkent waar de robot is, beacons die via bluetooth een singaal doorsturen, magnetische sensor (hell-effect-sensor), GEO-locatie o.b.v. radar, GEO-locatie obv Wi-Fi. Wat primair staat is dat de locatie herkenning op de centimeter nauwkeuring is kan herstellen van onverhoopte afwijkingen door bijvoorbeeld spelende kinderen of huisdieren. 





