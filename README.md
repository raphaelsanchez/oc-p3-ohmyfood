# OhMyFood - Révolutionnez le Monde de la Restauration

OhMyFood est une jeune startup ambitieuse qui vise à révolutionner l'industrie de la restauration en proposant une expérience culinaire unique et moderne. Notre projet combine la passion pour la nourriture de qualité avec les dernières avancées technologiques pour offrir à nos clients une expérience inoubliable.

## Technologies Utilisées

Le projet OhMyFood est développé en utilisant les technologies suivantes :

- HTML
- SCSS
- [pnpm](https://pnpm.js.org/)
- [Sass](https://www.npmjs.com/package/sass) version 1.64.2

## Scripts

Le projet est livré avec des scripts pratiques pour simplifier le développement et la production :

### Installation

Lancer manuellement l'installation des dépendances :

```bash
pnpm install
```

### Développement

Le script `dev` permet de surveiller les modifications dans les fichiers SCSS et de les compiler en un fichier style.css à la volée. Pour l'exécuter, utilisez la commande suivante :

```bash
pnpm run dev
```

### Production

Le script `build` est conçu pour la production. Il compile le fichier `/assets/scss/main.scss` en un fichier `/assets/css/style.css` compressé, prêt à être utilisé en production :

```bash
pnpm run build
```

## Structure du Projet

Le projet OhMyFood suit une architecture inspirée du modèle 7-1 pour le SCSS. Cela permet d'organiser et de structurer le code de manière clair et maintenable.

- `/abstracts` : Contient les fichiers SCSS abstraits, tels que les variables, les mixins et les fonctions. Ces fichiers ne génèrent pas de code CSS.
- `/base` : Contient les styles de base de l'application, tels que les styles de réinitialisation et les styles généraux.
- `/components` : C'est ici que les styles spécifiques aux composants sont stockés.
- `/layout`: Contient les styles de mise en page globaux, tels que la grille et les header/footer.
- `/pages` : Contient les styles spécifiques aux pages individuelles de l'application.
- `/utilities` : Contient les classes utilitaires et les styles génériques.

## Avertissement

Ce projet est réalisé à des fins éducatives dans le cadre d'un exercice d'intégration. OhMyFood est une plateforme fictive et toute ressemblance avec un site web existant est purement fortuite.

## Auteur

Ce projet a été réalisé avec amour par [Raphael Sanchez](mailto:hello@raphaelsanchez.design).
