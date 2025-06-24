# SerieA_coaches

Ce projet explore les trajectoires et caractéristiques des entraîneurs ayant dirigé des clubs de Serie A en Italie. Il a été réalisé dans le cadre du cours *Applications des méthodes numériques pour les sciences humaines et sociales* (UNINE, 2025).

## Objectifs
- Collecter des données depuis **Wikidata** (via SPARQL et Petscan)
- Construire une base structurée (CSV, SQLite, RDF)
- Répondre à des **questions de recherche** sur les parcours des entraîneurs
- Réaliser des analyses : temporelles, bivariées, en réseau, etc.

## Structure du dépôt
- `notebooks/` → Analyses Jupyter (pandas, SQL, graphes…)
- `data/` → Données intermédiaires et finales (CSV)
- `sparql/` → Requêtes SPARQL utilisées
- `documentation/` → Objectifs, catalogue de questions, synthèses

## Méthodologie
- Extraction des QIDs depuis [la page Wikipedia](https://en.wikipedia.org/wiki/Category:Serie_A_managers) via **Petscan**
- Requêtes SPARQL pour obtenir mandats, nationalités, parcours de joueurs, etc.
- Nettoyage, enrichissement et stockage dans **SQLite** puis export possible en **RDF**
- Visualisations avec `matplotlib`, `pyvis`, `networkx`…

## Analyses réalisées
- Évolution du nombre de coachs étrangers dans le championnat
- Influence de la nationalité sur le pays du club entraîné (test du Chi²)
- Réseau des clubs connectés par des entraîneurs communs
- Probabilité de coacher un club dans lequel on a déjà joué

---
*Projet réalisé par [Paul Micheli], juin 2025*
