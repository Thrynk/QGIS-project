# QGIS-project

Ce projet a pour but de visualiser l'évolution des crimes à Chicago depuis 2001 jusqu'à 2021.

Nous avons récupéré des données de BigQuery (un moteur de requêtes SQL distribué permettant d'effectuer des requêtes sur des données volumineuses en un temps minimal).
Nous nous sommes servis du jeu de données public suivant : Chicago Crime Data. Ce jeu de données est extrait du Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system.

Nous avons utilisé le plugin [BigQuery Layer](https://plugins.qgis.org/plugins/bigquerylayers/) que nous avons modifié afin de corriger certains bugs de lecture de fichiers.

Nous avons également utilisé les sources suivantes :
- police stations : https://data.cityofchicago.org/Public-Safety/Police-Stations-Map/gkur-vufi
- police districts : https://data.cityofchicago.org/Public-Safety/Boundaries-Police-Districts-current-/fthy-xz3r

Ces sources nous ont permis de générer le [carte finale](/final%20%map.svg).
