---
title: "Modder Avec Fabric"
date: 2022-01-14T22:23:14+01:00
weight: 20
---

Modder avec fabric est très facile. Il suffit de placer les bons fichiers au bons endroit, puis de rédemarrer le jeu.
Certains mods ont besoin parfois d'un peu de configuration, mais beaucoup marchent tels quel.
Voici un court tutoriel sur comment commder minecraft une fois fabric installé. Vous trouverez en bas de cette page quelques liens à propos de certains mods spécifiques].

{{< toc >}}

{{% notice warning %}}
Vous devez bien sur avoir installé minecraft et fabric. Si vous avez des soucis avec cette étape, consultez [cette page](/guide-technique/installer-fabric/)
{{% /notice %}}

## Trouver et choisir ses mods

### Les principales sources
Il y a de nombreux sites internet à partir desquels télécharger des mods. Néanmoins, certains sont plus populaires que d'autres, et les mods proposés dessus sont en général de meilleure "qualité" (moins prompts à beuguer/crasher) que les autres. De plus, les autres sites sont souvents des "mirroirs", sur lesquels les version distribuées ne sont pas à jour, et parfois même redistribuées sans le consentement de l'auteur du mod.

Voici une liste (non exhaustive) des sites les plus populaires :
  - [CurseForge](http://curseforge.com) : le plus connu, proposant le plus de choix
  - [Modrinth](http://modrinth.com/mods) : moins connu, plus récent, petit favori de certains moddeurs de par sa facilité d'emploi. Tout le sprojets publiés dessus sont nécessairement open-source. Moins de choix, mais des mods plus à jour et d'excellente qualité.
  - [ModRepo](http://modrepo.de) : toute petite base de mods, aux idées et fonctionnalités interessantes.

### A prendre en compte…
Quand vous choisissez un mod, vous devez faire attention à certaines choses pour en garantir le fonctionnement. Tout les mods sont au fond du bidouillage, et sont donc à même de rendre le jeu instable ou de dégrader les performances. A vous de vous assurer que le jeu est prêt à recevoir le mod et à le faire fonctionner. Certains paramètres sont cruxiaux à considérer en installant un mod.

#### Considérer de la version du jeu
Les mods sont écrits et publiés pour une version du jeu. Quand vous téléchargez le mod, assurez vous que ce soit la bonne. Un mod programmé pour la 1.17 ne marchera très probalement pas pour la 1.18 ou la 1.16. Par contre, il arrive q'un mod pour la 1.18 fonctionne en 1.18.1

#### Méditer sur le Modloader
Il y a quelques grandes familles de modloaders : Forge, Fabric et Spigot/Bukkit/Paper.
Un mod pour l'un de ces loader ne fonctionnera tout simplement pas sur les autres.

Beaucoups mods sont publiés pour plusieurs launchers : en général pour Fabric et Forge, mais certains moddeurs ont leur environnement de choix et s'y tiennent.

Nous utilisons le Fabric Mod Loader sur le serveur, car c'est celui qui impacte le moins le gameplay et les performances, qu'il propose tout de même beaucoup de choix de mods, et parce qu'il est simple à utiliser.  
Pour ces raisons, tout les conseils donnés sur notre wiki s'appliquent au Fabric mod loader seulement.

#### Pondérer les dépendences
Un mod est une extension de minecraft. Certains sont des programmes complexes. Ainsi, ils reposent souvent sur des dépendances, c'est à dire des "sous-mods" assez basiques qui ne font pas grand chose d'autre que de permettre à des projets plus grand de se développer.  
Chaque mod nécessite absolument ses dépendances, et si elles ne sont pas présentes, le jeu ne démarera tout simplement pas.

La dépendance la plus fréquemment retrouvée dans les mods Fabric est la FabricAPI, à tel point que je vous recommande de l'installer d'emblée.

### Mod Client ou Mod serveur ?
 1. Certains mods s'installent sur le [client](/lexique#client), c'est à dire sur votre machine de joueur. Vous pourrez utiliser ceux ci smplement en les installant sur votre machine, et cela ne regarde que vous.
 1. D'autres s'installent sur le [serveur](/lexique#serveur). Vous pourrez les utiliser simplement en vous connectant sur le serveur, et les installer sur votre machine n'aura pas d'effet, un peu à la façon d'un [datapack](/lexique#datapack)
 1. Enfin, certains doivent être présents sur les deux pour fonctionner correctement.
    - En général, ces mods empèchent les clients qui ne les ont pas installé de se connecter au serveur. Néanmoins, nous n'avons choisi que des mods qui permettent la connexion des clients vanilla.
    - Un client qui ne possède pas le mod pourra donc jouer, mais ne bénéficiera pas des fonctionnalités apportées par le mod.

{{% notice tip %}}
Si vous voulez proposer/demander l'installation d'un mod sur le serveur, lancez la discussion sur le discord ! toute suggestion est la bienvenue. Gardez à l'esprit que nous voulons tout de même conserver un aspect "vanilla-like" au jeu, et que nous preférons les mods qui n'excuent pas les clients non-moddés.
{{% /notice %}}

## Télécharger et installer un mod
La majorité des mods s'installent de façon assez simple. Il suffit de télécharger le fichier et de le glisser dans le dossier du jeu au bon endroit. Toutefois, il est bon de noter...
 - certains mods sont développés en différentes version. Il faut donc télécharger la bonne. cf [plus haut](#a-prendre-en-compte).
 - certains mods ont des méthodes d'installations plus compliquées. Elle sont généralement bien détaillées sur le site du développeur, et il faut alors les suivre.
 - parfois, le fichier téléchargé est un `.zip`. Dans ces cas là, il faut en général l'extraire pour en retirer le fichier `.jar` (sauf si le contraire est précisé par le mod)

Le dossier où placer les mods est différent selon votre système d'exploitation:
   - **{{< icon icon="fab fa-linux" >}} Linux / {{< icon icon="fab fa-apple" >}} MacOS**: `$HOME/.minecraft/mods`
   - **{{< icon icon="fab fa-windows" >}} Windows**: `%appdata%\minecraft\mods`
Si le dossier n'existe pas, il faut le créer.

## Zoom sur...
Certains mods nécessitent un peu de configuration ou bien une installation un peu particulière. Il n'est bien sûr pas possible de tous les lister ici, mais vous trouverez ici un abrégé du guide d'installation pour ceux utilisés par le serveur.

 - [Voicechat](../zoom/voicechat)
