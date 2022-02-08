---
title: "Worldmap"
date: 2022-01-31T13:09:42+01:00
type: "nouvelles"
author: "Topaway"
hidden: "true"
summary: "Le wiki dispose maintenant d'une worldmap ! Présentation sommaire..."
---

Les Worldmap... ces carte dynamiques auxquels les joueurs se réfèrent pour explorer, construire, échanger de bon tuyaux... tout serveur digne de ce nom se doit d'en avoir une !  
Jusqu'à maintenant, nous utilisions {{<small>}}(laborieusement){{</small>}} les map *in-game*, et quelques [générateurs en ligne](http://chunkbase.com/) utilisant la seed du monde pour prédire le terrain. Mais cette époque est révolue !

Maintenant, nous avons une ***véritable*** worldmap.

Générée grâce à un petit outil gratuit appelé [uNmINeD](https://unmined.net/), elle est de toute beauté, de très bonne résolution, dynamique... tout ce que nous aimons.  
Elle est surtout **directement intégrée dans le wiki** ! Le lien se trouve sur la page [Géographie](/monde/geographie), ainsi qu'ici : {{% button href="/worldmap/unmined.index.html" icon="fas fa-map-marked-alt" color="green" %}} Worldmap {{% /button %}}  
Ceci va nous permettre de ne pas nous prendre la tête à compresser les images et à devoir faire des compromis sur la qualité et les détails de la carte.

On peut même ajouter des marqueurs directement sur la carte. Pour le moment, seul le spawn est marqué, mais nous allons enrichir la carte de vos suggestion !

#### Comment suggérer un marqueur ?
1. Rendez vous sur le tableau google sheet ici : {{% button href="https://docs.google.com/spreadsheets/d/1-iLcY2G3Sv5r-BGLr9jhJj_qPGHWCF86DVuyeTJ8xyU" icon="fas fa-table" %}} Tableau des Points d'intérêt {{% /button %}}
2. Complétez les infos nécéssaires : 
    - nom du marqueur
    - coordonnées X, et Z, chacune dans sa case
    - couleur du texte en [hexadécimal](https://www.w3docs.com/tools/color-picker)
3. Envoyez moi un message pour que j'ajoute le marqueur sur la carte.

#### Points faibles du système
J'ai menti : la carte n'est pas *réellement* dynamique. Je dois la mettre manuellement à jour. Néanmoins, c'est assez facile et rapide à faire, et l'aspect de la carte sur le site est vraiment chouette.  
Bon, il est vrai que les noms des marqueurs est assez peu lisible si on en choisit mal la couleur. Pas grand chose que je puisse faire contre ça pour le moment.  
Dernière limite de cette implémentation : lorsque la carte se charge, elle s'ouvre centrée sur les coordonées 0:0, plutot que les coordonnées du spawn. Là encore, il nous faut nous y faire.

#### Avantages du système
La carte est légère, se charge facilement, détaillée et permet de zoomer facilement.  
Peu de services sur internet permette de mettre en ligne une image de cette taille et de cette qualité ! encore moins de pouvoir implémenter des marqueurs à celles ci. Je suis content d'avoir pu trouver une solution.

#### En bref...
La carte sera mise à jour de temps à autres. Elle devrait être facile d'accès pour nous tous, que ce soit sur ordinateur ou téléphone.  
N'hésitez pas à poser vos suggestions de marqueurs et d'améliorations !
