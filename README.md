# Geo-analyse boomdetectie demo
Demo open source geo-analyse met DeepForest en QGIS

Open source geo-analyse met AI en QGIS. In het voorbeeld zie je een shapefile van bomen, gegenereerd door het DeepForest beeldherkenning model vanuit een satellietfoto. AI doet het zoekwerk, de resulterende shapefile gebruik je daarna als laag in GIS zoals je gewend bent. 

Bomendetectie is een simpel voorbeeld en het DeepForest model werkt uit de doos zeker niet perfect op alle (Nederlandse) bomen (je kunt dit model wel nog verder finetunen met extra training). Maar het concept kan je ook voor andere onderwerpen en selectiemethodes toepassen. Het gaat er daarbij om dat je gelokaliseerde onderwerpen in TIF beelden (satelliet- of luchtfoto's met geo-informatie) correct transformeert naar vectordata in de shapefile. 

DeepForest gebruikt hier een module voor die je kunt hergebruiken. Zo kun je dit toepassen op andere AI-modellen, voor b.v. zonnepanelen of infrastructuur, maar ook op andere selectiemethodes zonder AI, zoals thresholding op pixelkleuren, infrarood waardes, enzovoort.

## Openen in QGIS
Open het projectbestand in de /qgis map... Deze laadt automatisch de door DeepForest aangemaakte shapefile en een WMTS achtergrond.

*NB: we hebben een beperkt gebied geanalyseerd! Als je uitzoomt zie je al snel de randen van het geanalyseerde gebied.*
## Links
Satellietdataportaal: https://www.satellietdataportaal.nl

DeepForest: https://github.com/weecology/DeepForest

QGIS: https://qgis.org