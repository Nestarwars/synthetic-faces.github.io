---
title: "La technologie derrière la génération de visages synthétiques"
collection: technology
type: ""
permalink: /technology/detection
---

Dans les articles de Microsoft, [3D Face Reconstruction with Dense Landmarks](https://microsoft.github.io/DenseLandmarks/) et [Fake It Till You Make It](https://microsoft.github.io/FaceSynthetics/) (Eroll Wood et al.), sont illustrés de nombreux aspects techniques de la synthèse de visages. 

Ces 2 travaux sont motivés par un fait : si l'on veut faire un détecteur de repères faciaux denses en utilisant des méthodes d'apprentissage profond, il faut avoir un grand ensemble de données densément annotées, et cela ne peut pas être fait, de manière cohérente et à grande échelle, par des humains. On a donc besoin d'un jeu de données entièrement synthétique, sur lequel les points de repère faciaux seront connus par construction.

Plusieurs approches sont possibles, détaillons-les ici, de la plus "manuelle" à la plus "automatique" : 

## Généreration entièrement à la main

## Génération partiellement basée sur des modèles paramétriques

## Génération entièrement réalisée avec des IA génératives