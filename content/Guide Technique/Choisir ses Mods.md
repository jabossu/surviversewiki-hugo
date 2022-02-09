---
title: "Choisir Ses Mods"
date: 2022-01-14T22:24:16+01:00
weight: 30
---

De nombreux mods existent pour Minecraft, mais tous ne sont pas compatibles avec Fabric ni avec Minecraft 1.18.1. Certains mods sont prévus pour le [serveur](/lexique#serveur), d'autres pour le [client](/lexique#cleint). La majorité ont besoin d'être installés sur les deux pour fonctionner correctement.

Notre serveur est *Vanilla-Like*, c'est à dire que nous essayons d'avoir le moins de mods possible, et que ceux que nous avons ne modifient pas d'aspect fondamental du jeu. Nous voulons garder le gameplay de Minecraft tout en améliorant la qualité de vie des joueurs.

Sur cette page, vous trouverez quelques informations sur les mods installés sur le serveur et sur ceux que vous pouvez choisir d'installer sur votre client.

{{< toc >}}

## Mods Serveur
Ces mods sont installés sur le serveur. La plupart sont des mods d'optimisation de performance, mais certains ajoutent quelques fonctionnalités. Ceux-ci ont été choisis pour tous être facultatifs ; c'est à dire que *vous **pourrez** vous connecter avec un client vanilla*. 

| Nom                     | Description                                          | Source       |
|-------------------------|------------------------------------------------------|--------------|
| **Fabric Loader & API** | Charge et gère les mods                              | [FabricMc](http://frabcricmc.net) |
| **Simple Voicechat**    | Chat de proximité ingame                             | [ModRepo](https://modrepo.de/minecraft/voicechat/overview/)      |
| **Sit (Fabric)**        | Asseyez vous !                                       | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/sit-fabric)     |
| **bfAPI**               | API nécessaire au mod Sit                            | [Mordrinth](https://modrinth.com/mod/bfapi)     |
| **Phosphore**           | Optimisation et gain de FPS                          | [Modrinth](https://modrinth.com/mod/phosphor)     |
| **Lithium**             | Optimisation et gain de RAM                          | [Modrinth](https://modrinth.com/mod/lithium)     |
| **Fabric-Discord Link** | Lie les messages de chat entre Discord et le Serveur | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/fabric-discord-link)     |

## Mods Clients-Serveur
Ces mods sont ceux qui nécessitent d'être installés sur le client *et* le serveur pour fonctionner. Certains empêcheront même les clients de se connecter s'ils ne sont pas installés.  
Néanmoins, nous n'avons aucun de ces mods sur notre serveur. Autrement dit, *même un client vanilla pourra se connecter et jouer normalement*.

Le seul mod client-serveur que nous avons est le **Simple Voice Chat**, on mod de chat de proximité. Ses principales fonctionnalités sont:
 - Un chat vocal *ingame*, ne nécessitant pas d'application tierce
 - Le volume des joueurs est lié à la distance qui les sépare
    - approchez vous simplement d'un autre joueur pour l'entendre et lui parler, sans passer par un menu
    - paniquez en entendant sa voix se faire plus distante et faible à mesure que vous vous perdez dans les cavernes
 - Créez des groupes de chat pour parler à plusieurs, quelque soit la distance qui vous sépare
 - Mode Push-to-Talk ou Voice Detection 
 - Paramétrez le mod *ingame*
    - réglez le volume des autres joueurs
    - changez le seuil d'activation de votre micro

## Mods Clients Recommandés
Voici une liste suggestive et non-exhaustive de mods pratiques, utilisables en étant seulement installés sur le client. 

### Optimisation et gain de performance
| Nom            | Description                                                                                                                                                                                                                                                                        | Source                                                                                                                                                     |
|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **cullLeaves** | Optimisation graphique : modifie le rendering des feuilles pour n'afficher que celles visibles. Gain de performances particulièrement notable dans les régions avec beaucoup d'arbres.  NB: Peut etre associé avec un ressourcepack pour garder un aspect esthétique aux feuilles. | [Modrinth](https://modrinth.com/mod/cull-leaves) RessourcePack: [BetterLeaves](https://www.curseforge.com/minecraft/texture-packs/motschens-better-leaves) |
| **lithium**    | Optimisation du moteur de jeu réduisant lag et diminuant les ressources consommées.                                                                                                                                                                                                | [Modrinth](https://modrinth.com/mod/lithium)                                                                                                               |
| **phosphor**   | Optimisation du moteur d'éclairage du jeu améliorant les performances.                                                                                                                                                                                                             | [Modrinth](https://modrinth.com/mod/phosphor)                                                                                                              |
| **sodium**     | Optimisation du moteur d'affichage améliorant les performances                                                                                                                                                                                                                     | [Modrinth](https://modrinth.com/mod/sodium)                                                                                                                |
| **krypton**    | Optimisation du protocole d'échange de paquets avec le serveur améliorant la connexion.                                                                                                                                                                                            | [Modrinth](https://modrinth.com/mod/krypton)                                                                                                               |
| **lazydfu**    | Ne charge que les données nécessaires, accélérant considérablement le lancement du jeu.                                                                                                                                                                                            | [Modrinth](https://modrinth.com/mod/lazydfu)                                                                                                               |                                                                                          |        |

### Modifications de l'interface et gain de fonctionnalités
| Nom                       | Utilité | Description                                                                                          | Source                                                                    |
|---------------------------|---------|------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------|
| **clickthrough**          | ⭐⭐⭐     | Cliquez et accédez aux coffres au travers des pancartes                                              | [Modrinth](https://modrinth.com/mod/clickthrough)                         |
| **easiercrafting**        | ⭐⭐      | Améliore l'interface de craft pour obtenir le même résultat en moins de clics                       | [Modrinth](https://modrinth.com/mod/easiercrafting)                       |
| **easiervillagertrading** | ⭐⭐      | Améliore l'interface des villageois pour obtenir le même résultat en moins de clics                 | [Modrinth](https://modrinth.com/mod/easiervillagertrading)                |
| **stendhal**              | ⭐⭐⭐⭐    | Modifie l'interface de texte pour offrir couleurs, émotions et style aux livres, nametags et chats | [Modrinth](https://modrinth.com/mod/stendhal)                             |
| **InventoryProfilesNext** | ⭐⭐⭐⭐⭐   | Un petit outil pour trier et ranger les inventaires en quelques raccourcis                          | [Modrinth](https://modrinth.com/mod/inventory-profiles-next)              |
| **MouseTweaks**           | ⭐⭐      | Gérez vos inventaires et déplacez les objets en quelques clicks                                      | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/mouse-tweaks)   |
| **light-overlay**         | ⭐⭐⭐     | Mettez en surbrillance les blocks où les mobs peuvent spawner                                      | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/light-overlay/) |
| **statuseffecttimer**     | ⭐⭐⭐     | Affichez sur votre écran le temps restant aux effets de potions                                      | [Modrinth](https://modrinth.com/mod/statuseffecttimer)                    |
| **inspecio**              | ⭐⭐⭐⭐⭐   | Obtenez plus d'infos sur vos objets en les survolants de votre souris                                | [Modrinth](https://modrinth.com/mod/inspecio)                             |

### Librairies & Dépendances
Ces mods sont les fondations sur lesquelles reposent les autres. Vous devrez les installer pour permettre au jeu de fonctionner.  
Voici le détail des dépendances :
 - Fabric Loader: pas vraiment un mod, mais nécessaire pour tout jeu moddé
 - Fabric API: 
 - modmenu
 - cloth-config
 - architectury

