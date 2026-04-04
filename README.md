# cartes-ign-topographie

## Informations générales

URL : https://ed94120.github.io/cartes-ign-topographie/

L'application extrait une image géoréférencée à partir d'une carte IGN sur laquelle on peut superposer différents overlays.

Un des overlays donne la position des supports d'antennes. Les positions sont récupérées des fichiers open data ANFR qui se trouvent dur le site dtata.gouv.fr. 

Fichier du repository cartes-ign-topographie contenant la position des supports d'antennes : "./data/GeoJSON-support_antennes_ANFR-light-aaaa-mm-jj.geojson".

Le fichier est mis à jour régulièrement.

## Mise à jour du fichier contenant la position des antennes

URL pour récupérer les informations ANFR sur les supports d'antennes : https://www.data.gouv.fr/datasets/donnees-sur-les-installations-radioelectriques-de-plus-de-5-watts-1

Format du nom des Fichiers ZIP récupérés : aaaammjj-export-etalab-data.zip

Nom du fichier à l'intérieur du fichier ZIP contenant les coordonnées latitude et longitude des supports : SUP_SUPPORT.txt

Le fichier SUP_SUPPORT.txt doit ensuite être converti en fichier geoJSON.

La conversion est réalisée avec l'application accessible avec cette URL : https://ed94120.github.io/anfr-supports-to-geojson/
