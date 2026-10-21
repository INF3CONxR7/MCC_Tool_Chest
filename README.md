# MCC Tool Chest

**MCC Tool Chest** est un utilitaire Windows destiné à l'exploration, à l'édition et à la conversion de mondes de **Minecraft: Legacy Console Edition**, notamment sur **PlayStation 3** et **Xbox 360**.

Ce dépôt `MCC_Tool_Chest` contient une **distribution Windows compilée** du logiciel ainsi qu'une **présentation non officielle**. Il ne prétend pas être le projet original ni être affilié à ses créateurs. Le code source de l'application n'est pas inclus.

## Fonctionnalités

- **Édition NBT** : consulter et modifier les données de mondes, d'entités et de blocs-entités.
- **Gestion des chunks** : examiner les régions et intervenir sur certains chunks.
- **Édition de mondes** : outils de remplacement de blocs et de biomes selon la version et le format pris en charge.
- **Conversion** : convertir certains mondes Minecraft PS3/Xbox 360 vers le format PC et inversement.
- **Extraction et sauvegarde** : extraire les données d'un monde et générer les fichiers de sauvegarde compatibles avec le format source.

> Les fonctionnalités disponibles varient selon la version du logiciel, la plateforme et le format du monde.

## Plateformes et formats

| Plateforme / format | Prise en charge |
| --- | --- |
| Minecraft PlayStation 3 | Édition et conversion de sauvegardes compatibles |
| Minecraft Xbox 360 | Édition et conversion de sauvegardes compatibles |
| Minecraft Java / PC (anciennes versions) | Conversion sous certaines conditions |
| Fichiers `.mcs` isolés | Compatibilité à vérifier selon le fichier et la version utilisée |

**Attention :** MCC Tool Chest (console) est différent de **MCC Tool Chest PE**, destiné à d'autres formats de Minecraft. Tous les formats et toutes les versions de Minecraft ne sont pas compatibles.

## Installation

1. [Téléchargez ce dépôt au format ZIP](https://github.com/INF3CONxR7/MCC_Tool_Chest/archive/refs/heads/main.zip), ou utilisez **Code → Download ZIP** sur GitHub.
2. Extrayez entièrement l'archive dans un dossier sur Windows.
3. Conservez `MCCToolChest.exe`, `MCCToolChest.exe.config`, toutes les DLL et le dossier `support/` ensemble.
4. Lancez `MCCToolChest.exe` depuis le dossier extrait.

La configuration fournie cible **.NET Framework 4.0**. Si un composant Windows requis manque, consultez les dépendances indiquées sur la [page de téléchargement du logiciel](https://mcctoolchest.weebly.com/download.html).

> Cette copie est fournie telle quelle ; ce dépôt ne garantit pas la maintenance ni la compatibilité du logiciel avec toutes les versions de Windows ou de Minecraft.

## Utilisation avec une sauvegarde PS3

1. Faites une **copie de sauvegarde** de votre monde avant toute modification.
2. Récupérez les fichiers du monde PS3 que vous êtes autorisé à modifier.
3. Ouvrez MCC Tool Chest et utilisez les fonctions d'extraction ou d'ouverture adaptées au format de la sauvegarde.
4. Modifiez les données nécessaires, puis enregistrez ou exportez le résultat.
5. Si nécessaire, **resignez la sauvegarde PS3** avec un outil compatible avant son utilisation sur la console.
6. Testez d'abord le monde modifié sur une copie.

Les sauvegardes PS3 peuvent notamment utiliser un fichier `GAMEDATA`. La procédure exacte dépend de l'origine et de la structure de la sauvegarde.

## À propos des fichiers `.mcs`

Ce dépôt s'intéresse également aux fichiers `.mcs` rencontrés dans l'écosystème Minecraft Legacy Console. **L'ouverture et l'édition directes d'un fichier `.mcs` isolé ne sont pas garanties** par toutes les versions de MCC Tool Chest. Vérifiez le format exact du fichier avant de tenter une modification.

## Avertissements

- Sauvegardez toujours les fichiers originaux.
- Des modifications incorrectes peuvent corrompre un monde ou le rendre illisible.
- Certains mondes récents ou formats particuliers peuvent être incompatibles.
- Le logiciel est un outil communautaire tiers, non officiel et non affilié à Mojang ou Microsoft.

## Crédits et sources

**MCC Tool Chest n'a pas été créé par le propriétaire de ce dépôt.** Tous les droits sur le logiciel, son code et ses ressources restent à leurs titulaires respectifs.

Des sources publiques associent le développement de MCC Tool Chest à **A Cynodont** et **RedstonerLab(s)**. Consultez les sources originales pour les crédits complets et les conditions de redistribution.

- [Site MCC Tool Chest](https://mcctoolchest.weebly.com/)
- [Téléchargement et dépendances](https://mcctoolchest.weebly.com/download.html)
- [Tutoriel et fonctions](https://mcctoolchest.weebly.com/tutorial.html)
- [Présentation sur Planet Minecraft](https://www.planetminecraft.com/mod/mcc-tool-chest/)

## Licence et redistribution

Aucune licence open source n'est présumée pour les fichiers tiers. **Avant de publier des exécutables, du code ou des ressources du logiciel dans ce dépôt, vérifiez les droits de redistribution correspondants.** La présente documentation ne transfère aucun droit sur le logiciel original.

---

*Dépôt communautaire non officiel consacré à MCC Tool Chest et à son utilisation avec Minecraft Legacy Console Edition.*
