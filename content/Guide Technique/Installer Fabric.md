---
title: "Installer Fabric"
date: 2022-01-14T22:23:00+01:00
weight: 10
---

> Premiers pas pour Modder votre jeu avec Fabric

{{< toc >}}

## Pourquoi Fabric ?

Il existe plusieurs systèmes différents pour modder Minecraft. Forge est le plus connu, mais il existe aussi Spigot, Bukkit, Paper... Celui qui est à la mode depuis un certain temps est Fabric, et c'est celui que nous utilisons sur le serveur des Star Survivors.  

**Les avantages de Fabric**
 - la facilité d'installation
 - la légèreté et l'économie des ressources
 - les mises à jours rapides
 - la large bibliothèque de mods disponibles

## le Fabric Loader
 
{{% notice tip %}}
L'installation décrite ici concerne la version officielle de Minecraft, telle que téléchargée sur [minecraft.net](http://minecraft.net).  
D'autres méthodes d'installation existent, notamment pour les lanceurs alternatifs comme [MultiMC](https://fabricmc.net/wiki/player:tutorials:install_multimc:windows)
{{% /notice %}}

### Prérequis
 - un compte Minecraft
 - Minecraft installé, ayant été lancé au moins une fois

### Installation

1. Téléchargez l'installateur sur [<i class="fa-solid fa-link"></i>fabricmc.net](http://fabricmc.net)
   - **<i class="fa-brands fa-linux"></i> Linux / <i class="fa-brands fa-apple"></i> MacOS**: choisissez le fichier `.JAR`
   - **<i class="fa-brands fa-windows"></i> Windows**: choisissez l'`installateur windows`
2. Executez l'installateur
   - **<i class="fa-brands fa-linux"></i> Linux / <i class="fa-brands fa-apple"></i> MacOS**:
     - Ouvrez un Terminal et naviguez vers le dossier où se trouve l'installateur (probablement le dossier de téléchargements)
     - Tapez la commande suivante : 
         ```bash
         java -jar fabric-installer-0.xx.xx.jar
         ```
   - **<i class="fa-brands fa-windows"></i> Windows**: exécutez le fichier `.exe` que vous venez de télécharger 
5. Une fenêtre s'ouvre et vous demande de choisir la version de fabric et de minecraft.
     - choisissez la dernière version de fabric
     - choisissez minecraft 1.18.1
3. Ouvrez Minecraft, choisissez le nouveau profile "*Fabric*"
   - NB: Si le profile n'apparaît pas, il y a eu une erreur d'installation
4. Jouez & Enjoy

### Mise à jour

 - Suivez exactement le même processus que pour l'[installation](#installation)
 - Choisissez le nouveau profile créé au lieu de l'ancien
   - vous pouvez supprimer l'ancien profile

### Troubleshooting

 - **Echec de l'installation**: Vérifiez que Java SE v17 est bien installé
 


