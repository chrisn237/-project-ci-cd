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
