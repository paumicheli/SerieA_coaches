# Objectifs du projet

## Contexte

Ce projet vise à expérimenter l'ensemble du processus de production et d'analyse d'information sous forme de données. Le thème choisi est la population des entraîneurs de football ayant exercé en Serie A (championnat d'Italie de première division).

La liste de référence utilisée est celle des entraîneurs recensés sur Wikipédia :  
https://en.wikipedia.org/w/index.php?title=Category:Serie_A_managers

Les données ont été collectées via des requêtes SPARQL, nettoyées et structurées dans une base relationnelle (SQLite) à l’aide de SQLiteStudio. Certaines expérimentations ont également été menées sur AllegroGraph pour manipuler les données au format RDF.

## Problématique générale

Comprendre les profils, trajectoires et évolutions des entraîneurs ayant officié en Serie A, à travers une approche fondée sur l’analyse de données.

Ce projet s’intéresse notamment aux questions suivantes :
- Quelles sont les nationalités, les âges, les parcours types ?
- Quel lien existe entre l’expérience de joueur et la carrière d’entraîneur ?
- Comment la profession a-t-elle évolué dans le temps ?
- Quels clubs jouent un rôle central dans les parcours des entraîneurs ?

## Objectifs spécifiques

- **Collecte et structuration des données** :
  - Identifier les entraîneurs depuis Wikipédia et récupérer leurs QIDs Wikidata.
  - Récupérer les données biographiques et professionnelles via SPARQL.
  - Construire une base de données SQLite comportant plusieurs tables : entraîneurs, clubs, mandats, carrières de joueur.
  - Tester l’import des données sous forme RDF dans AllegroGraph.

- **Analyse exploratoire et statistique** :
  - Documenter les analyses dans des notebooks Jupyter.
  - Réaliser des analyses univariées (distribution par pays, âge…) et bivariées (test du Chi-2).
  - Réaliser une analyse de réseau pour visualiser les liens entre clubs via les entraîneurs.

- **Visualisation des données** :
  - Générer des graphiques et visualisations (notamment en réseau) pour illustrer les résultats.

## Livrables

Le dépôt GitHub contient :
- Le catalogue des questions de recherche (`docs/catalogue_questions.md`)
- La définition des objectifs du projet (`docs/objectifs_projet.md`)
- Le code SPARQL documenté (`sparql/`)
- 3 à 5 notebooks Jupyter pour les analyses (`notebooks/`)
- Les synthèses rédigées (`docs/syntheses/`)
- L'export de la base RDF compressée (`rdf_export/`)
- 
*Date : juin 2025*



