---
layout: page
title: Liste des dépôts
permalink: /repo/
---
##[DISIC/rgaa_referentiel](https://github.com/DISIC/rgaa_referentiel/blob/master/README.md)
###Version 3.0 du référentiel général d'accessibilité pour les administrations

Ce dépôt comporte l'ensembe des documents constituant la version 3.0 du RGAA :
* Introduction au RGAA
* Guide d'accompagnement
* Référentiel technique

Ces documents sont rédigés en Markdown. Vous trouverez sur ce [lien wikipedia](https://fr.wikipedia.org/wiki/Markdown) des précisions sur ce langage.

##[DISIC/rgaa\_bibliotheques\_javascript](https://github.com/DISIC/rgaa_bibliotheques_javascript)
###Accessibilité des bibliothèques JavaScript

Une étude de l'accessibilité des principales bibliothèques JavaScript a donné lieu à deux types de ressources :

* un état des lieux du niveau d'accessibilité des différents composants actuels ;
* une correction des composants accompagné d'un tutoriel expliquant comment corriger.

Voici les bibliothèques étudiées :

* jQuery + jQuery-ui ;
* Bootstrap + plugin Paypal ;
* AngularJS + AngularUI Bootstrap ;
* React.

Nous savons les limites de l'exercice, les bibliothèques étant amenées à évoluer. Ce projet vise à initier une démarche pour remonter les problèmes auprès des différents éditeurs de bibliothèques et les aider à prendre en compte l'accessibilité dans les développements de base.

##[DISIC/rgaa\_composants\_javascript](https://github.com/DISIC/rgaa_composants_javascript)
###Composants JavaScript accessibles

Cette plateforme de test présente les implémentations des composants ARIA telles qu'elles sont définies par les motifs de conception.

Elle permet d'établir les restitutions par défaut obtenues avec les technologies d'assistance définies par la base de référence.

Cette bibliothèque est destinée à servir de référence pour les tests de restitution demandés par le test 7.6 du critère 7.1 du référentiel RGAA. Elle n'est pas destinée à être utilisée en production.

Note 1: certains enrichissements, nécessaires à une restitution correcte, sont décrits pour chaque composant. Ces enrichissements ne sont pas demandés par les motifs de conception ARIA car ils sont contextuels à la nature et l'utilisation du composant ou de ses contenus.

Note 2: les interactions au clavier sont limitées à celles requises par le référentiel.

####Liste des composants de cette section

- Potentiomètre
- Barre de progression
- Fenêtre de dialogue
- Système d'onglet
- Infobulle
- Bouton d'action
- case à cocher
- barre de menu
- accordéon
- arborescence
- calendrier de saisie
- liste d'autocomplétion
