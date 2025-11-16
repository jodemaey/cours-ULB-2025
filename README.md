# Cours ULB PHYS-F-450 Météorologie dynamique (2025): Application pratique avec Python

Cette série de notebooks est un complément pour le cours [PHYS-F-450](https://www.ulb.be/fr/programme/phys-f450-1) donné à l'ULB.
Les pré-requis sont

* Avoir suivi la première partie du cours.
* Être familié avec le language de programmation Python

Le cours utilise le framework [qgs](https://github.com/Climdyn/qgs) pour la modélisation climatique et météorologique d'ordre réduit.
Dans ce cours, vous apprendrez :

1. Comment installer le framework qgs
2. Comment exécuter le modèle
3. Comment calculer le plus grand exposant de Lyapunov d'un modèle, et le lien avec sa prévisibilité
4. Comment calculer le spectre complet des exposants de Lyapunov

En outre, le cours se clôture sur l'étude d'un modèle plus avancé, intégrant un couplage entre l'atmosphère et l'océan.


## Installation requise

Pour installer qgs et ces exercices, vous devez d'abord installer qgs sur votre ordinateur.
Suivez pour ce faire les [instructions d'installation](https://github.com/Climdyn/qgs#installation), en utilisant `pip`.
Ensuite, clonez le dépôt des exercices dans un terminal avec la commande

    git clone git@github.com:jodemaey/cours-ULB-2025.git

qui installera ceux-ci dans le répertoire `cours-ULB-2025`.

Vous pouvez ensuite vous rendre dans ce répertoire et lancer

    jupyter-notebook

pour atterir sur l'interface de [Jupyter](https://jupyter.org/) et lancer les notebooks.

> Remarque: La façon de cloner avec git et de lancer Jupyter peut différer si vous êtes sous Windows. 

## Introduction à Python et à Numpy

Dans la suite, nous allons utiliser Python et la librairie de calcul [Numpy](https://numpy.org/).
Pour apprendre le language Python si vous ne le maîtrisez pas déjà, nous suggérons deux liens:

1. Le site de Python lui-même: https://www.python.org/doc/
2. Le module Python 3 sur la CodeAcademy: https://www.codecademy.com/learn/learn-python-3

Pour apprendre à utiliser Numpy, nous suggérons la page sur le site officiel: https://numpy.org/learn/.
Celle-ci contient un grand nombre de tutoriaux, livres et vidéos.

**Dans tous les cas, nous allons avancer pas-à-pas, donc vous pouvez apprendre le language en parallèle de cette série de notebooks.**

## Détail des notebooks

Ci-dessous, le détail de chaque notebook contenu dans le cours est détaillé.
Les notebooks seront ajoutés au fur et à mesure de la progression du cours.

Nous commençons par une introduction préliminaire:

### Notebook 0 - Introduction à Python et qgs

Ce [premier notebook](./Cours%20PHYS-F-450%20--%20Notebook%200%20-%20Introduction.ipynb) sert d'introduction au framework qgs. Il doit être parcouru et effectué par l'étudiant avant les cours en présentiel. Son but est de montrer comment utiliser le modèle, de vous permettre de vous familiariser avec ses paramètres, et de finalement l'intégrer pour déterminer ses trajectoires. Il se termine par une série d'exercices facultatifs.

