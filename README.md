# Geo-analyse boomdetectie demo
Demo open source geo-analyse met DeepForest en QGIS

Open source geo-analyse met AI en QGIS: met de juiste brondata en technologie automatisch GIS data samenstellen. In het voorbeeld zie je een shapefile van bomen, gegenereerd door het DeepForest beeldherkenning model vanuit een satellietfoto. AI doet het zoekwerk, de resulterende shapefile gebruik je daarna als laag in GIS zoals je gewend bent. 

Bomendetectie is een simpel voorbeeld en het DeepForest model werkt uit de doos zeker niet perfect op alle (Nederlandse) bomen (je kan dit model finetunen met extra training). Maar ook voor andere onderwerpen en selectiemethodes kun je dit toepassen. 

Het gaat er daarbij om dat je gelokaliseerde onderwerpen in TIF beelden (satelliet- of luchtfoto's met lokatiedata) correct transformeert naar vectordata in de shapefile. DeepForest gebruikt hier een module voor die je evt. kunt hergebruiken. Zo kun je dit toepassen op andere AI-modellen (voor b.v. zonnepanelen of infrastructuur) maar ook op andere selectiemethodes zoals pixelkleuren, infrarood waardes, enzovoort.

## Links
Satellietdataportaal: https://www.satellietdataportaal.nl
DeepForest: https://github.com/weecology/DeepForest
QGIS: https://qgis.org