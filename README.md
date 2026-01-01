# TP 28 : SonarQube (local) — Analyse d'un projet Java Maven

## Description
Ce TP apprend à installer SonarQube en local avec Docker, à créer un projet et générer un token, puis à analyser un projet Java Maven via la commande `mvn clean verify sonar:sonar`. L'activité montre comment interpréter le Quality Gate (Passed/Failed) et exploiter les résultats (Bugs, Code Smells, Vulnérabilités, Security Hotspots, couverture et duplications) afin de prioriser les corrections et améliorer progressivement la qualité, la maintenabilité et la sécurité du code.

## Objectif de l'activité
Mettre en place SonarQube en local (Docker), créer un projet, générer un token, lancer l'analyse d'un projet Java Maven, puis interpréter les résultats (Quality Gate, bugs, odeurs de code, vulnérabilités, couverture…).

## Structure du projet
Ce projet contient des classes Java simples avec des tests JUnit pour démontrer l'analyse SonarQube :

- `DateUtils.java` : Utilitaire pour les calculs de dates
- `StringTools.java` : Outils de manipulation de chaînes de caractères
- Tests JUnit correspondants avec couverture JaCoCo

## Prérequis
- Docker Desktop (ou Docker Engine)
- Navigateur Web
- JDK 17 installé
- Maven (ou Maven Wrapper mvnw)

## Utilisation pour le TP
1. Suivre les étapes du TP pour installer SonarQube avec Docker
2. Créer un projet dans SonarQube
3. Générer un token d'analyse
4. Exécuter l'analyse avec Maven : `mvn clean verify sonar:sonar`
5. Consulter les résultats dans l'interface SonarQube