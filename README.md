# Projet 8 — Analyser l'évolution de profils sociodémographiques avec dbt et Snowflake

## Présentation du projet

Ce projet consiste à exploiter des données sociodémographiques afin d'étudier la répartition et l'évolution des profils d'étudiants selon différentes dimensions, notamment l'âge, le sexe, la région et l'année de début des études.

L'objectif est de préparer des données fiables et structurées pour faciliter leur analyse et produire des indicateurs pertinents pour le suivi des populations étudiantes.

## Objectifs

- Structurer et transformer les données à l'aide de dbt.
- Exploiter Snowflake comme environnement de stockage et de traitement des données.
- Analyser la répartition des étudiants selon les régions, les classes d'âge et le sexe.
- Calculer des indicateurs permettant de comparer les populations étudiantes.
- Préparer un jeu de données exploitable pour la visualisation et l'analyse décisionnelle.

## Méthodologie

1. **Exploration des données** : identification des variables disponibles et compréhension de leur structure.
2. **Transformation avec dbt** : organisation des transformations nécessaires à la préparation des données.
3. **Traitement dans Snowflake** : exploitation de l'entrepôt de données pour structurer les données et réaliser les calculs.
4. **Construction des indicateurs** : préparation de mesures relatives aux effectifs, à la répartition des étudiantes et à la proportion d'étudiants dans la population.
5. **Restitution** : documentation du workflow et présentation de la démarche et des résultats.

## Indicateurs étudiés

Le jeu de données final comprend notamment les variables suivantes :

- Nombre d'étudiants.
- Pourcentage d'étudiantes.
- Effectif total de la population.
- Population correspondant à chaque classe d'âge.
- Nombre d'étudiants pour 100 000 habitants.
- Part des étudiants dans la région.

Ces indicateurs permettent d'étudier les différences entre régions et de comparer la représentation des étudiants au regard de la population.

## Outils et technologies

- **Snowflake** : stockage et traitement des données dans un entrepôt de données cloud.
- **dbt** : organisation et automatisation des transformations de données.
- **SQL** : interrogation et transformation des données.
- **CSV** : export du jeu de données préparé pour l'exploitation.

## Livrables

- [Jeu de données final au format CSV](./Capell_Gabriel_1_fichier_052026.csv)
- [Documentation du workflow](./Capell_Gabriel_2_workflow_052026.pdf)
- [Support de présentation](./Capell_Gabriel_3_presentation_052026.pdf)

## Compétences développées

- Transformation et structuration des données.
- Utilisation de dbt et Snowflake.
- Manipulation de données avec SQL.
- Construction d'indicateurs sociodémographiques.
- Préparation de données pour l'analyse décisionnelle.
- Documentation d'un workflow de traitement des données.

## Conclusion

Ce projet m'a permis de mettre en pratique une démarche de transformation de données avec dbt et Snowflake, depuis l'exploration des données jusqu'à la production d'un jeu de données structuré.

Il illustre l'utilisation d'un entrepôt de données et d'un outil de transformation pour préparer des indicateurs adaptés à l'analyse de profils sociodémographiques.

---

**Domaine :** Data Analytics et ingénierie des données  
**Outils principaux :** dbt, Snowflake, SQL  
**Type de projet :** Transformation et analyse de données sociodémographiques  
**Formation :** Data Analyst  
**Dépôt GitHub :** [projet8data](https://github.com/gbcpl/projet8data)
