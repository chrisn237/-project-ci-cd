# Projet CI/CD avec GitHub Actions

## Description
Ce projet met en place un pipeline (CI/CD) via GitHub, automatisant les étapes de **Build**, **Test**, et **Deploy**.

## Pipeline CI/CD
- **Build** : Simule la création de l'application en utilisant Docker.
- **Test** : Exécute deux tests en parallèle pour valider le code.
- **Deploy** : Simule le déploiement en affichant un message de succès avec la variable d'environnement `DEPLOY_ENV`.

## Technologies
- **GitHub Actions** pour l'automatisation.
- **Docker** pour un environnement de build standardisé.

## Installation
1. Cloner le projet :
   ```bash
   git clone https://github.com/chrisn237/-project-ci-cd.git

## optimisation pipeline
1. Installation centralisée des dépendances : Un job setup installe les dépendances et partage les artefacts entre les jobs pour éviter les réinstallations.
2. Exécution parallèle des tests : Les tests sont parallélisés via une matrice de jobs, réduisant le temps d’exécution global.
3.  Déploiement conditionnel : Le déploiement se déclenche uniquement sur la branche main et lors de la création d’un tag.
