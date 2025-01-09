# Projet utilisant Drone CI/CD

Ce dépôt utilise Drone CI/CD pour l'intégration et le déploiement continus.

## Configuration

Le pipeline CI/CD est défini dans le fichier `.drone.yml` à la racine du projet. Ce fichier spécifie les étapes du pipeline, telles que la construction, les tests et le déploiement[1].

## Fonctionnement

Drone CI/CD est une plateforme moderne de CI/CD basée sur une architecture centrée sur les conteneurs. Elle permet de configurer facilement des projets pour automatiser la construction, les tests et le déploiement à chaque modification du code[8].

Lorsqu'un commit est poussé sur le dépôt, Drone CI/CD :

1. Clone le dépôt
2. Exécute les étapes définies dans le fichier `.drone.yml`
3. Affiche les résultats dans l'interface web de Drone

## Avantages

- Intégration native avec GitHub[7]
- Configuration simple via le fichier YAML[1]
- Exécution de chaque étape dans un conteneur isolé[8]
- Large choix de plugins disponibles[8]

Pour plus d'informations sur la configuration et l'utilisation de Drone CI/CD, consultez la [documentation officielle](https://docs.drone.io/).