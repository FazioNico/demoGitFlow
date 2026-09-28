# Git Flow Demo

## Vue d'ensemble

Ce dépôt démontre l'utilisation du modèle **Git Flow** pour la gestion des versions et des branches en développement logiciel.

## Modèle Git Flow

![Git Flow Model](./git-model@2x.png)

## Branches principales

- **main** : Branche de production, contient les versions stables et taguées
- **develop** : Branche de développement, point d'intégration pour les nouvelles fonctionnalités
- **feature/** : Branches de fonctionnalités, créées à partir de `develop`
- **release/** : Branches de préparation de version, créées à partir de `develop`
- **hotfix/** : Branches de correction d'urgence, créées à partir de `main`

## Flux de travail typique

1. Créer une branche `feature/ma-fonctionnalite` depuis `develop`
2. Développer et commiter les changements
3. Créer une Pull Request vers `develop`
4. Après approbation, fusionner dans `develop`
5. Préparer une version via `release/`
6. Fusionner dans `main` et tagger la version

## Contribution

Pour contribuer, suivez le modèle Git Flow décrit ci-dessus.
