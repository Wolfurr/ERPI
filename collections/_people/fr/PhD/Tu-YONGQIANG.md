---
title: Tu YONGQIANG
permalink: /people/Tu-YONGQIANG/
excerpt: "Évaluation et contrôle de la qualité pour l'écriture directe à l'encre bioink"
last_modified_at: 2020-08-28
author: Tu
header:
  teaser: /assets/images/people/PHD/Tu-YONGQIANG.jpg

orden: YONGQIANG
role: PHD
---

## Expérience et contact 


1. Conception et analyse de l'amortisseur à mécanisme parallèle
2. Analyse de l'erreur de navigation dans le système de navigation inertielle à rotation à deux axes (RINS).

[![Google Scholar](/assets/images/people/PHD/scholar.png){:height="70px" width="70px"}](https://scholar.google.com/citations?user=cELZ2BMAAAAJ&hl=fr) [![ResearchGate](/assets/images/people/PHD/researchgate.png){:height="70px" width="70px"}](https://www.researchgate.net/profile/Yongqiang_Tu)
 
[![LinkedIn](/assets/images/people/PHD/linkedin.png){:height="70px" width="70px"}](https://www.linkedin.com/in/勇强-涂-14a6671b5/) ![Email](/assets/images/people/PHD/mail.png){:height="70px" width="70px"} tuyq1992 {at} gmail.com



## Titre de la thèse 

**Évaluation et contrôle de la qualité pour l'écriture directe à l'encre bioink**

## Résumé

En raison de la combinaison des avantages en termes de coût, de prospérité non toxique, de disponibilité en grandes quantités, de durabilité environnementale, les bioinks innovants fabriqués à partir de fibres végétales sont très prometteurs dans de nombreuses applications médicales et industrielles, y compris l'ingénierie tissulaire et régénérative, les batteries, les capteurs, la fabrication alimentaire , l'impression en quatre dimensions (4D), les produits de la vie civile, etc., qui leur font gagner une grande attention tant dans l'industrie que dans le monde universitaire. La fabrication additive (FA) peut fournir des conceptions personnalisées, une complexité structurelle élevée, une fabrication rapide à la demande à faible coût, de sorte que diverses technologies AM ont été utilisées comme bio-impression pour les bioinks, y compris l'impression à jet d'encre, la bio-impression assistée par laser (y compris impression et impression directe induite par laser), bio-impression par stéréolithographie (SLA) et écriture directe à l'encre par extrusion (DIW). Parmi ces méthodes AM, la bio-impression DIW présente les avantages les plus importants en termes de flexibilité des matériaux, de faible coût et de capacité à construire des structures 3D arbitraires requises pour les progrès à travers des frontières multidisciplinaires par rapport à d'autres technologies, de sorte que la bio-impression DIW est l'une des principales techniques d'impression 3D pour les bioinks . Cependant, en tant que nouvelle technologie, de nombreuses études devraient être menées pour améliorer la qualité de la pièce finale par DIW à base de bioink. Les principaux goulots d'étranglement qui limitent la bio-impression dans DIW pour les bioinks comprennent trois aspects:

1. L'absence d'une méthode complète et quantitative pour évaluer l'imprimabilité des bioinques dans le but de sélectionner un bioinque approprié.
2. Le manque de cadre complet pour la sélection et l'optimisation des paramètres de processus pour la bio-impression DIW pour un certain bioink, un certain modèle 3D et une certaine machine.
3. L'absence de schéma en boucle fermée pour contrôler le processus DIW.


Afin de résoudre ces problèmes, un cadre d'évaluation et de contrôle de la qualité de la bio-impression DIW à base de bioinque devrait être proposé. En tant que base la plus importante pour ce cadre, des expressions complètes et quantitatives pour les propriétés des bioinks et le processus DIW sont essentielles pour l'évaluation de l'imprimabilité des bioinks, la sélection et l'optimisation des paramètres de processus ainsi que le contrôle des processus, qui est également l'un des principaux objectifs de cette thèse. Par conséquent, dans la première partie de la thèse, les propriétés des bioinks liées au processus sont étudiées et décrites mathématiquement en premier lieu. Les propriétés des bioinks liées au procédé DIW comprennent la densité, la tension superficielle et le modèle de viscosité. La densité et la tension superficielle peuvent être facilement obtenues par des instruments sous forme de constantes. La propriété de viscosité décrit la relation entre la viscosité et le taux de cisaillement des bioinks. Les variations de viscosité avec le taux de cisaillement et les données de viscosité liées au taux de cisaillement sont obtenues par des expériences de viscosité en utilisant un rhéomètre. Un algorithme hybride de réflexion de la région de confiance (TRRA) et un algorithme génétique (GA) sont conçus pour la sélection du modèle de viscosité. Ensuite, des simulations numériques des procédés d'extrusion incluant l'extrusion dans l'air et l'extrusion sur le substrat sont réalisées sur OpenFOAM® pour explorer le procédé d'impression. Pour la simulation de l'extrusion dans l'air, le débit de la bioinque est basé sur la méthode des volumes finis (FVM), et la capture pour l'interface entre la bioinque et l'air est basée sur la méthode du volume de fluide (VOF). Pour la simulation de l'extrusion sur le substrat, en plus de l'écoulement et de la capture pour l'interface entre la bioink et l'air comme l'extrusion dans l'air, le mouvement de la buse a utilisé une approche de mouvement de maille basée sur un solveur pour laplacien de la diffusivité et de la vitesse de mouvement de la cellule. Sur la base de la simulation, l'ensemble du processus DIW pourrait être étudié comme un système à entrées et sorties multiples (MIMO). Les entrées comprennent les propriétés de la bioinque (densité, tension superficielle, modèle de viscosité) et les paramètres de processus (vitesse du piston, vitesse de la buse, espace entre la buse et le substrat). Les sorties incluent la vitesse et la forme du filament extrudé dans l'air; forme de la pièce finale sur le substrat. Ensuite, des tests d'impression pour l'extrusion dans l'air et l'extrusion sur le substrat sont effectués pour vérifier la méthode de sélection du modèle de viscosité proposée pour les bioinks et des simulations du processus d'extrusion dans DIW.  


Basé sur le système MIMO pour la bio-impression DIW basée sur la bioinque obtenu par la première partie de la thèse, dans la deuxième partie, le deuxième objectif de la thèse, qui sont l'évaluation de l'imprimabilité des bioinques, la sélection et l'optimisation des paramètres de processus ainsi que le contrôle de processus basé sur le Système MIMO, sont étudiés respectivement.
Pour l'évaluation de l'imprimabilité des bioinks, le but est de proposer une méthode d'évaluation des bioinks avec certaines propriétés imprimables ou non pour une certaine machine DIW. Plusieurs méthodes expérimentales ont été développées. Cependant, les méthodes expérimentales nécessitent du temps, du matériel et les mesures de certains paramètres critiques du processus sont limitées dans la capacité de test pendant les expériences. Pour résoudre ces problèmes, une méthode de simulation pour évaluer l'imprimabilité des bioinques en bioimpression DIW est proposée en complément des méthodes expérimentales. Premièrement, les propriétés physiques des bioinks, y compris la densité, le coefficient de tension superficielle et le modèle de viscosité, sont caractérisées à l'aide de tests de matériaux et d'analyses de données. Ensuite, la méthode d'évaluation par simulation comporte deux étapes. La première étape consiste à simuler le filament extrudé dans l'air pour obtenir les profils de forme et de vitesse du filament. La deuxième étape consiste à simuler les filaments sur le substrat et à caractériser l'imprimabilité bioinque en fonction du profil de forme des filaments sur le substrat. Enfin, une méthode expérimentale a été menée pour vérifier la méthode d'évaluation proposée.
Pour la sélection et l'optimisation des paramètres de processus ainsi que le contrôle de processus, nous commencerons ces deux contenus à partir de la deuxième année.


## Directeurrs 

Dr. Alaa Hassan; Prof. Ali Siadat; Prof. Yang Gongliu

## Financeurs

China Scholarship Council (CSC) scholarship (No. 201906020135)

