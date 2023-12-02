![prediction](https://github.com/theobonzi/epita_machine_learning/assets/55917899/73814ded-2b4e-4ad8-9a2a-093b6850af3f)# 🌈 Projet de Classification de Pixels sur Images Hyperspectrales et LiDAR

## Contexte du Projet

Pour ce projet, les données utilisées sont celles du [_IEEE GRSS Data Fusion Contest 2013_](http://www.classic.grss-ieee.org/community/technical-committees/data-fusion/2013-ieee-grss-data-fusion-contest/). Le Data Fusion Contest de l'IEEE GRSS (Geoscience and Remote Sensing Society) est un concours annuel organisé par les membres du chapitre GRSS de l'association IEEE. Ce challenge est ouvert à tous les chercheurs, doctorants, étudiants, etc., et vise à explorer des problématiques de fusion d'information pour des applications en télédétection.

![rgb](https://github.com/theobonzi/epita_machine_learning/assets/55917899/b1d5174c-fc4f-4191-a792-75076703c5e7)
![prediction](https://github.com/theobonzi/epita_machine_learning/assets/55917899/38bc3440-1354-4659-af6b-b49d8369115d)

## Données du Projet

Les données utilisées pour ce projet ont été acquises au-dessus de l'université de Houston en 2012. Elles se composent de deux types d'images :

- **Image Hyperspectrale** : Comprend 144 bandes couvrant la portion de $380-1050~nm$ du spectre électromagnétique.
- **Image LiDAR** : Fournit des informations complémentaires à l'image hyperspectrale.

Les deux images sont à la même résolution spatiale de 2.5 m/pixel et sont co-registrées, assurant que chaque pixel de l'une couvre exactement la même surface au sol que le pixel correspondant de l'autre image.

## Objectifs du Projet

L'objectif principal de ce projet est de classifier les pixels des images hyperspectrales et LiDAR pour identifier les classes d'objets (de 1 à 15) auxquelles ils appartiennent. Pour atteindre cet objectif, nous suivons une approche méthodique comprenant plusieurs étapes clés :

1. **Prétraitement des Données** : Normalisation, suppression de nuages, et égalisation d'histogramme pour préparer les images pour l'analyse.
2. **Sélection des Meilleures Bandes** : Utilisation de techniques de corrélation et de variance pour choisir les bandes les plus informatives.
3. **Fusion des Données Hyperspectrales et LiDAR** : Combinaison des deux types d'images pour tirer parti de leurs informations complémentaires.
4. **Test de Modèles de Classification et Méthodes de Réduction de Dimension** : Évaluation de divers modèles et techniques pour déterminer la meilleure approche de classification.
5. **Interprétation des Résultats** : Analyse approfondie des performances des modèles pour identifier le plus efficace.
