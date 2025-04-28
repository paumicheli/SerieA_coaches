# Objectifs du projet

## Contexte

Ce projet vise à expérimenter l'ensemble du processus de production et d'analyse d'information sous forme de données. Le thème choisi est la population des entraîneurs de football ayant exercé en Serie A (championnat d'Italie de première division).

Les données principales proviendront de Wikidata et seront modélisées sous forme de base RDF, stockée sur un serveur AllegroGraph.

## Problématique générale

Comprendre les caractéristiques et trajectoires typiques des entraîneurs de Serie A à partir d'analyses de données :
- Profils socio-démographiques
- Parcours de joueur
- Évolution des tendances au fil du temps
- Facteurs qui pourraient prédisposer à une carrière d'entraîneur

## Objectifs spécifiques

- **Collecte de données** :
  - Extraire les informations pertinentes depuis Wikidata via des requêtes SPARQL.
  - Nettoyer et organiser les données dans une base RDF sur AllegroGraph.

- **Analyse des données** :
  - Documenter et réaliser plusieurs analyses à l'aide de notebooks Jupyter.
  - Comparer les caractéristiques des entraîneurs selon diverses dimensions (nationalité, âge, ancienneté, parcours de joueur).

- **Visualisation** :
  - Produire des graphiques clairs pour illustrer les résultats.

- **Synthèse** :
  - Répondre à 3 à 5 questions de recherche à travers des pages en Markdown ou HTML.

## Livrables

- Un dépôt GitHub contenant :
  - Le catalogue des questions de recherche (`docs/catalogue_questions.md`)
  - La définition des objectifs du projet (`docs/objectifs_projet.md`)
  - Le code SPARQL documenté (`sparql/`)
  - 3 à 5 notebooks Jupyter pour les analyses (`notebooks/`)
  - Les synthèses rédigées (`docs/syntheses/`)
  - L'export de la base RDF compressée (`rdf_export/`)

---

*Date : avril 2025*

