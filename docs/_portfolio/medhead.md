---
classes: wide
date: 2023-01-30T03:02:20+00:00
title: "MedHead"
excerpt: "La plateforme nationale de soins et d'intervention d'urgence a besoin de vous !"
header:
  image: /assets/images/medhead.png
  teaser: assets/images/medhead-th.png
# sidebar:
#   - title: "Role"
#     image: http://placehold.it/350x250
#     image_alt: "logo"
#     text: "Designer, Front-End Developer"
#   - title: "Responsibilities"
#     text: "Reuters try PR stupid commenters should isn't a business model"
categories:
  - CI-CD
  - Java
  - Docker
  - AWS
# tags:
#   - categories
#   - edge case
gallery:
  - url: https://github.com/GitSDamien/OC_11_Medhead_ERS/blob/main/docs/Architecture_metier.md
    image_path: https://raw.githubusercontent.com/GitSDamien/OC_11_Medhead_ERS/main/docs/images/presentation/8.png
    alt: "L'architecture métier"
  - url: https://github.com/GitSDamien/OC_11_Medhead_ERS/blob/main/docs/Docker_Environnement.md
    image_path: https://raw.githubusercontent.com/GitSDamien/OC_11_Medhead_ERS/main/docs/images/presentation/9.png
    alt: "L'environnement Docker"
  - url: https://github.com/GitSDamien/OC_11_Medhead_ERS/blob/main/docs/AWS_Architecture.md
    image_path: https://raw.githubusercontent.com/GitSDamien/OC_11_Medhead_ERS/main/docs/images/presentation/10.png
    alt: "L'architecture AWS"
  - url: https://github.com/GitSDamien/OC_11_Medhead_ERS/blob/main/docs/GitHubActions_pipeline.md
    image_path: https://raw.githubusercontent.com/GitSDamien/OC_11_Medhead_ERS/main/docs/images/presentation/11.png
    alt: "Pipeline CI-CD"
---


MedHead, un consortium de prestigieuses institutions médicales britanniques soumis aux réglementations et aux directives locales du NHS, désire standardiser les plateformes et les technologies utilisées par ses membres en adoptant `Java` en tant que langage principal. Un comité d'architecture s'est réuni pour examiner un projet visant à atténuer les risques associés au traitement des recommandations de lits hospitaliers en cas d'urgence. Nous avons recommandé de concevoir une preuve de concept pour tester cette hypothèse.

En plus de la mise en place de la `pipeline CI/CD`, la majeure partie du travail a porté sur la recherche d'un environnement de travail efficace pour les développeurs, tout en préservant un niveau de sécurité élevé.

Le premier dépôt Git comprend le code Java avec une configuration CI/CD pour générer des `rapports d'essais inspectables`, dotés de `tests automatisés` basés sur un plan de test et des `scénarios BDD` (Behavior Driven Development) qui définissent les tests d'acceptation.

[https://github.com/GitSDamien/OC_11_Medhead_ERS](https://github.com/GitSDamien/OC_11_Medhead_ERS){:target="_blank" }

Il se divise en quatre parties :

1. [**L'architecture métier**](https://github.com/GitSDamien/OC_11_Medhead_ERS/blob/0661b9eeaeb6d4e45e6859946bf48890a396f9a8/docs/Architecture_metier.md){:target="_blank" } : définition du problème et d'une solution
2. [**L'environnement Docker**](https://github.com/GitSDamien/OC_11_Medhead_ERS/blob/0661b9eeaeb6d4e45e6859946bf48890a396f9a8/docs/Docker_Environnement.md){:target="_blank" } : déploiement d'un environnement de développement en moins de dix minutes
3. [**L'architecture AWS**](https://github.com/GitSDamien/OC_11_Medhead_ERS/blob/0661b9eeaeb6d4e45e6859946bf48890a396f9a8/docs/AWS_Architecture.md){:target="_blank" } : haute disponibilité et élasticité, infrastructure réplicable
4. [**La Pipeline CI/CD**](https://github.com/GitSDamien/OC_11_Medhead_ERS/blob/0661b9eeaeb6d4e45e6859946bf48890a396f9a8/docs/GitHubActions_pipeline.md){:target="_blank" }, sympa GitHub Actions

{% include gallery %}

Le second dépôt est la base architecturale et comprend une hypothèse de validation de principe, une stratégie de test, une documentation sur les principes d'architecture et une description des éléments de base réutilisables obtenus au cours de la conception et de la mise en production. Les principes et les justifications de l'architecture sont documentés en détail, ainsi que les travaux d'architecture personnalisés selon les `normes TOGAF`.

[https://github.com/GitSDamien/OC_11_Architectural](https://github.com/GitSDamien/OC_11_Architectural){:target="_blank" }


*Support de présentation*
![](https://raw.githubusercontent.com/GitSDamien/OC_11_Medhead_ERS/a1b9a4c121f806f1446a0a6c985d18c6a09c86c2/docs/images/presentation/ERS.gif)

