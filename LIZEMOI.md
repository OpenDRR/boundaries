  Toutes les géométries de ce repo sont générées au format GeoPackage et compressées au format 7-Zip.
  7-Zip peut être téléchargé et installé à l'adresse https://www.7-zip.org/.

# boundaries
Géométries des limites pour les résultats du modèle. Toutes les géométries sont au format EPSG 4326.

 - Géométrie_ADAUID.7z
	- Géométrie de l'aire de diffusion des agrégats
 - Geometry_CANADA.7z
	- Géométrie du contour du Canada
 - Géométrie_CDUID.7z
	 - Géométrie des divisions de recensement
 - Géométrie_CSDUID.7z
	- Géométrie de la subdivision de recensement, polygone simplifié à 0,005 degrés. 
 - Géométrie_DAUID.7z
	- Géométrie de la zone de diffusion
 - Géométrie_ERUID.7z
	- Géométrie de la région économique
 - Géométrie_FSAUID.7z
	- Géométrie de la zone de triage aval
 - Géométrie_SAUID.7z
	 - Géométrie de la région colonisée
 - LandGov_v1.csv
	 - Registre de toutes les zones colonisées et si elles sont gérées sous l'autorité provinciale/territoriale ou par le biais d'autres cadres de gestion des terres comme les terres indiennes, les réserves indiennes ou les revendications territoriales.
 
  Adapté de Statistique Canada, Recensement de 2016 - Fichiers des limites, 2020. Cela ne constitue pas une approbation de ce produit par Statistique Canada.

## hexgrid_4326

La collection de grilles hexagonales est une série de géométries et de tableaux hexagonaux élaborés pour aider les utilisateurs à visualiser les couches nationales d'établissements humains à différents niveaux d'agrégation hexagonale en dehors des limites conventionnelles du recensement.  Les géométries de la grille hexagonale ont été créées dans QGIS à l'aide du plugiciel MMQGIS en utilisant les limites des frontières canadiennes, provinciales et territoriales à divers espacements de grille.  Les tables de référence sont générées et contiennent les informations nécessaires à l'agrégation des couches nationales d'établissements humains jusqu'à la géométrie de grille hexagonale donnée.  Toutes les géométries sont conformes à la norme EPSG 4326.

 - HexGrid_1km_{P/T}.gpkg, HexGrid_1km_{P/T}_unclipped.7z
    - Géométrie hexagonale clippée/déclippée des provinces et territoires basée sur un espacement de grille x d'environ 0,01 degré.
 - HexGrid_5km.7z, HexGrid_5km_unclipped.7z
    - Géométrie hexagonale coupée/coupée du Canada basée sur un espacement de grille x d'environ 0,05 degré.
 - HexGrid_10km.7z, HexGrid_10km_unclipped.7z
    - Géométrie hexagonale écrêtée/décalée du Canada basée sur un espacement de grille x d'environ 0,1 degré.
 - HexGrid_25km.7z, HexGrid_25km_unclipped.7z
    - Géométrie hexagonale coupée/coupée du Canada basée sur un espacement de grille x d'environ 0,25 degré.
 - HexGrid_50km_unclipped.7z
    - Géométrie hexagonale non rognée du Canada basée sur un espacement de grille x d'environ 0,5 degré.
 - HexGrid_100km_unclipped.7z
    - Géométrie hexagonale non tronquée du Canada basée sur un espacement de grille x d'environ 1 degré.
 - HexGrid_GlobalFabric.7z
    - Étendues de la géométrie hexagonale du Canada basées sur la grille hexagonale du tissu global de GEM.
 - SAUID_HexGrid.7z, SAUID_HexGrid_unclipped.7z
	- Tableau référençant le centroïde de chaque identifiant de zone colonisée (SAUID) aux différentes géométries HexGrid (5km, 10km, 25km, 50km, 100km) utilisées à des fins d'agrégation.
- SAUID_HexGrid_1km_intersect.7z, SAUID_HexGrid_1km_intersect_unclipped.7z
	- Tableau référençant la zone de l'identifiant de la zone colonisée (SAUID) et son pourcentage d'intersection de zone par rapport à la géométrie HexGrid_1km_{P/T} utilisé à des fins d'agrégation.
- SAUID_HexGrid_5km_intersect.7z, SAUID_HexGrid_5km_intersect_unclipped.7z
	- Tableau référençant la zone de l'identifiant de la zone colonisée (SAUID) et son pourcentage d'intersection de zone par rapport à la géométrie HexGrid_5km utilisée à des fins d'agrégation.
- SAUID_HexGrid_10km_intersect.7z, SAUID_HexGrid_10km_intersect_unclipped.7z
	- Tableau référençant la zone de l'identifiant de la zone colonisée (SAUID) et son pourcentage d'intersection de zone par rapport à la géométrie HexGrid_10km utilisée à des fins d'agrégation.
- SAUID_HexGrid_25km_intersect.7z, SAUID_HexGrid_25km_intersect_unclipped.7z
	- Tableau référençant la zone de l'identifiant de la zone colonisée (SAUID) et son pourcentage d'intersection de zone par rapport à la géométrie HexGrid_25km utilisée à des fins d'agrégation.
- SAUID_HexGrid_50km_intersect_unclipped.7z
	- Tableau faisant référence à la zone d'identification de la zone colonisée (SAUID) et à son pourcentage d'intersection de zone par rapport à la géométrie HexGrid_50km utilisée à des fins d'agrégation.
- SAUID_HexGrid_100km_intersect_unclipped.7z
	- Tableau faisant référence à la zone d'identification de la zone colonisée (SAUID) et à son pourcentage d'intersection de zone par rapport à la géométrie HexGrid_100km utilisée à des fins d'agrégation.
- SAUID_HexGrid_GlobalFabric_intersect.7z
	- Tableau faisant référence à la zone de l'identifiant de la zone réglée (SAUID) et à son pourcentage d'intersection de zone par rapport à la géométrie HexGrid_GlobalFabric utilisée à des fins d'agrégation.

## hexgrid_3857

Collection de grilles hexagonales similaire à hexgrid_4326 mais créée en EPSG 3857. Reportez-vous à hexgrid_4326 pour la description.
