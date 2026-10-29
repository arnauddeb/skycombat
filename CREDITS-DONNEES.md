# Sources et crédits — SkyCombat 3D

## Photographies aériennes et relief

**© IGN — BD ORTHO® et RGE ALTI®**, Géoplateforme, extraits et services consultés le **28 octobre 2026**, sous **Licence Ouverte / Open Licence 2.0**.

- Photographies aériennes : couche `ORTHOIMAGERY.ORTHOPHOTOS`, service WMS Raster : https://data.geopf.fr/wms-r/wms
- Altitudes : ressource `ign_rge_alti_wld`, service de calcul altimétrique : https://data.geopf.fr/altimetrie/1.0/calcul/alti/rest/elevation.json
- Fiche BD ORTHO, producteur IGN et licence : https://www.data.gouv.fr/datasets/bd-ortho-r
- Documentation WMS : https://cartes.gouv.fr/aide/fr/guides-utilisateur/utiliser-les-services-de-la-geoplateforme/diffusion/wms-raster/
- Documentation altimétrie et limite de débit : https://cartes.gouv.fr/aide/fr/guides-utilisateur/utiliser-les-services-de-la-geoplateforme/calcul-altimetrique/
- Texte de la licence : https://www.data.gouv.fr/pages/legal/licences/etalab-2-0

Les images intégrées sont des extraits assemblés et compressés. Les altitudes sont échantillonnées puis interpolées ; la surface de la piste est adaptée au jeu. La date ci-dessus est celle de l’extraction, pas une affirmation sur l’année des prises de vue. Pour les autres lieux, le jeu utilise la couche disponible au moment du chargement. La couverture du fournisseur peut varier selon les territoires.

## Aéroports et aérodromes

**OurAirports**, données du domaine public, téléchargées le 28 octobre 2026 : https://ourairports.com/data/

Référentiels : https://davidmegginson.github.io/ourairports-data/airports.csv et https://davidmegginson.github.io/ourairports-data/runways.csv

L’extrait retient les aéroports/aérodromes ouverts du référentiel en France et dans les territoires français. Il comprend 1 326 entrées. Les 52 entrées des Hauts-de-France sont repérées par la région `FR-HDF`. Les grands aéroports sont ceux classés « large_airport » ou disposant de services réguliers dans le référentiel. La longueur, la largeur, l’orientation et le centre de piste sont utilisés lorsqu’ils sont renseignés ; à défaut, le jeu utilise l’identifiant de piste ou un aménagement générique. Ce n’est pas une reproduction détaillée de chaque aéroport.

## Communes

**API Géo / Découpage administratif**, référentiel public Etalab, Licence Ouverte 2.0. Extrait de 34 969 communes avec noms, codes, départements et centres, téléchargé le 28 octobre 2026.

- API : https://geo.api.gouv.fr/communes?fields=nom,code,centre,codeDepartement&format=json
- Documentation : https://geo.api.gouv.fr/decoupage-administratif/communes

## Moteur et création

Three.js, licence MIT : voir `vendor/THREE-LICENSE.txt` (également conservée dans les fichiers à publier).

Jeu créé par Martin à l’aide de l’IA. Cockpits et éléments du jeu modélisés dans les sources du projet. GeoFS a servi de référence visuelle via les captures fournies ; aucun modèle, texture de cockpit ou code GeoFS n’est repris.
