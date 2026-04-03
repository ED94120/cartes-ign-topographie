# cartes-ign-topographie

URL : https://ed94120.github.io/cartes-ign-topographie/

L'application extrait une image géoréférencée à partir d'une carte IGN sur laquelle on peut superposer différents overlays.

Un des overlays donne la position des antennes-relais en mars 2026. Les positions sont récupérées des données open data ANFR. 

Fichier du repository contenant la position des supports des antennes : "./data/GeoJSON-support_antennes_ANFR-light-2026-04-03.geojson"

URL pour récupérer les localisations des supports d'antennes : https://www.data.gouv.fr/datasets/donnees-sur-les-installations-radioelectriques-de-plus-de-5-watts-1

Format du nom des Fichiers ZIP récupérés : 20260228-export-etalab-data.zip

Nom du fichier contenant les coordonnées des supports dans le fichier ZIP : SUP_SUPPORT.txt

Le fichier SUP_SUPPORT.txt doit ensuite être converti en fichier geoJSON.

La conversion est réalisée avec l'application qui est accessible avec cette URL : https://ed94120.github.io/anfr-supports-to-geojson/
