# Donkey Kong – WPF

Reproduction en C# / WPF d'un niveau du jeu d'arcade Donkey Kong (1981) : le joueur doit atteindre le sommet du niveau le plus vite possible en évitant barils et boules de feu.

Projet réalisé dans le cadre de la **SAé 2.01** du BUT Informatique (IUT de Dijon), en équipe de 4, en juin 2025.

## Fonctionnalités

- Déplacements, sauts, échelles, collisions avec barils et boules de feu
- Marteau et bonus, score, 3 vies avec retour au début du niveau
- Écrans d'accueil, de victoire et de défaite
- Paramètres : volume, choix des touches, langue (français / anglais)

## Architecture

```
Donkey_Kong_Metier/   Logique du jeu : joueur, items (barils, échelles, plateformes…), score, paramètres
Donkey_Kong_IHM/      Interface WPF : fenêtres, sons, ressources de traduction (.resx)
Test*/                Tests unitaires : collisions, mouvements, paramètres, sauvegarde
IUTGame.dll           Bibliothèque de jeu 2D fournie par l'IUT
```

Séparation entre la logique métier et l'interface, avec tests unitaires sur la logique.

## Stack

C# / .NET 8 · WPF · tests unitaires · Git/GitHub

## Lancer le projet

Sous Windows, ouvrir `Donkey_Kong.sln` dans Visual Studio et lancer le projet `Donkey_Kong_IHM`.

## Équipe

Audigier · El Allam · Souveton · Himeur

Dépôt d'origine : [dept-info-iut-dijon/2024_S2-01_B2_donkey_kong](https://github.com/dept-info-iut-dijon/2024_S2-01_B2_donkey_kong)

*Projet pédagogique sans but commercial. Donkey Kong est une marque de Nintendo.*
