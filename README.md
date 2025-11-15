# Cours ULB PHYS-F-450 Météorologie dynamique (2025): Application pratique avec Python

Cette série de notebooks est un complément pour le cours [PHYS-F-450](https://www.ulb.be/fr/programme/phys-f450-1) donné à l'ULB.
Les pré-requis sont

* Avoir suivi la première partie du cours.
* Être familié avec le language de programmation Python

Dans ce cours, vous apprendrez :

1. Comment installer le framework qgs pour la modélisation climatique et météorologique d'ordre réduit
2. Comment exécuter le modèle
3. Comment calculer le plus grand exposant de Lyapunov d'un modèle, et le lien avec sa prévisibilité
4. Comment calculer le spectre complet des exposants de Lyapunov

En outre, le cours se clôture sur l'étude d'un modèle plus avancé, intégrant un couplage entre l'atmosphère et l'océan.

## Installation requise

Pour installer qgs et ces exercices, vous devez d'abord installer [Anaconda](https://www.anaconda.com/) sur 
votre ordinateur portable. Ensuite, clonez le dépôt qgs et suivez 
les [instructions d'installation](https://github.com/Climdyn/qgs#installation). 
Vous pouvez ensuite copier les notebooks de cette série dans le **répertoire racine** de qgs et le tour est joué !

## Introduction à Python et à Numpy

Dans la suite, nous allons utiliser Python et la librairie de calcul [Numpy](https://numpy.org/).
