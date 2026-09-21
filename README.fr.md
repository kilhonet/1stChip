# 1stChip

**Les caractéristiques et les pilotes de votre PC en un coup d'œil.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · Français

> Ce document est une traduction. En cas de divergence, la [version coréenne](README.ko.md) fait foi.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20x64-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-0.9.0-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/1stchip?lang=fr)

![1stChip screenshot](images/1stchip-ko.webp)

## Présentation

1stChip affiche ce que contient votre PC — processeur, carte mère, carte graphique, multimédia, carte réseau et autres périphériques — sur un seul écran, avec la version et la date du pilote installé pour chacun.

Il fonctionne même sur un Windows fraîchement installé : un périphérique apparaît dans la liste avec son fabricant même si aucun pilote n'est encore installé et que le Gestionnaire de périphériques n'affiche que « Périphérique inconnu ». C'est très pratique juste après une installation propre, quand il faut savoir quels pilotes manquent encore.

Il suffit de décompresser et de lancer. Pas d'installation, pas de droits d'administrateur, rien d'autre à installer.

## Fonctionnalités

- **Résumé du matériel sur un écran** — processeur, carte mère, carte graphique, multimédia, carte réseau et autres périphériques, chacun avec le logo du fabricant.
- **Version et date du pilote installé** pour chaque périphérique, affichées sous son nom.
- **Fonctionne sans pilotes** — les périphériques sans pilote sont tout de même listés avec leur fabricant et marqués `!`.
- **Vérification des mises à jour de pilotes** — la liste est comparée au serveur 1stChip ; lorsqu'un pilote plus récent est connu, le périphérique est marqué et une infobulle indique la version disponible.
- **Un clic vers la page du pilote** — cliquez sur la marque `!` pour ouvrir la page du pilote de ce périphérique.
- **Ligne système** en bas : fréquence du processeur, mémoire totale et édition/version de Windows.
- **Les périphériques en double sont regroupés** — les périphériques identiques n'apparaissent qu'une fois, sous la forme `(×N)`.
- **Portable** — un seul EXE que vous pouvez emporter sur une clé USB.
- **Aucun droit d'administrateur requis.**
- **Suit Windows** — mode sombre ou clair selon le thème des applications Windows ; langue de l'interface selon la langue d'affichage de Windows (anglais, coréen).

## Téléchargement / Installation

| Paquet | Lien |
|---|---|
| Installateur | [Télécharger](https://down.kilho.net/1stchip?lang=fr) |
| Portable (ZIP) | [Télécharger](https://down.kilho.net/1stchip?lang=fr&nosetup) |

1stChip est disponible en version **portable** : téléchargez le ZIP, décompressez-le où vous voulez et lancez `1stChip.exe` — aucune installation nécessaire. Il fonctionne aussi très bien depuis une clé USB.

## Utilisation

### Le déroulement de base

1. Lancez `1stChip.exe`. La liste du matériel apparaît en quelques secondes.
2. La liste est regroupée ainsi : **Processeur → Carte mère → Carte graphique → Multimédia → Carte réseau → Autres périphériques**. La première ligne de chaque catégorie est le périphérique représentatif ; les autres suivent en gris.
3. Sous le nom de chaque périphérique figurent la **version et la date du pilote installé**.
4. Une marque jaune `!` signale qu'il y a quelque chose à vérifier. Survolez-la pour en connaître la raison et **cliquez** pour ouvrir dans le navigateur la page du pilote de ce périphérique.
5. Le bas de la fenêtre affiche la fréquence du processeur, la taille de la mémoire et la version de Windows.

La liste est lue une fois au démarrage. Après avoir installé un pilote, fermez et relancez 1stChip pour voir le résultat.

### La fenêtre

| Partie | Ce qu'elle montre |
|---|---|
| Logo | Logo du fabricant (initiales pour les fabricants sans logo) |
| Nom du périphérique | Le nom attribué par Windows. Les périphériques identiques sont regroupés sous la forme `(×2)` |
| Deuxième ligne | Version · date du pilote installé |
| `!` | Pas de pilote / problème / pilote plus récent connu — survolez pour savoir lequel, cliquez pour la page du pilote |
| Panneau du bas | Fréquence du processeur (de base) · taille de la mémoire · système d'exploitation |

### Comment…

**Vous venez d'installer Windows et ne savez pas quels pilotes installer**
Lancez 1stChip et repérez les périphériques marqués `!`. Si le survol indique « Aucun pilote n'est installé », c'est que ce périphérique n'a pas de pilote. Cliquez sur `!` pour ouvrir la page du pilote, installez-le, puis relancez 1stChip pour vérifier que le `!` a disparu. Si le PC n'a pas d'Internet faute de pilote réseau, utilisez 1stChip pour lire le fabricant et le modèle de la carte réseau, puis récupérez le pilote depuis un autre PC.

**Le Gestionnaire de périphériques affiche un « Périphérique inconnu »**
Le Gestionnaire de périphériques ne peut pas nommer un périphérique sans pilote, mais 1stChip en identifie le fabricant et la catégorie sans pilote. Trouvez le périphérique dans sa catégorie et cliquez sur `!`.

**Vérifier si vos pilotes sont à jour**
Lorsqu'un pilote plus récent est connu, le périphérique reçoit un `!` et le survol affiche « Vous pouvez mettre à jour vers la version x.x.x ». Sans `!`, il est à jour dans la limite de ce qui est connu.

**Consulter rapidement les caractéristiques du PC**
Lisez seulement la première ligne (périphérique représentatif) de chaque catégorie et vous avez le processeur, le chipset de la carte mère, la carte graphique, le son et la carte réseau d'un coup d'œil, avec la taille de la mémoire et la version de Windows dans le panneau du bas. Pratique pour rédiger une annonce de vente ou comparer avec la configuration recommandée d'un jeu.

**Plusieurs périphériques identiques**
Les périphériques identiques sont regroupés sur une ligne avec un compteur tel que `(×2)`. Les périphériques structurels dont vous n'avez jamais à vous soucier — concentrateurs USB, ponts internes — sont exclus de la liste.

**Contrôler de nombreux PC**
1stChip ne nécessite ni installation ni droits d'administrateur : gardez-le sur une clé USB et lancez-le sur chaque PC. Il ne laisse aucune trace sur le PC où il s'exécute.

**Sur un PC sans Internet**
La liste du matériel et les détails des pilotes installés fonctionnent entièrement hors ligne. Seules les marques « pilote plus récent disponible » et la page du pilote ouverte en cliquant sur `!` nécessitent une connexion.

**La fenêtre est sombre (ou claire), ou en anglais**
1stChip suit Windows. Changez le mode clair/sombre dans Windows *Paramètres → Personnalisation → Couleurs → Mode d'application*, et la langue de l'interface via la langue d'affichage de Windows (coréen → coréen, toute autre → anglais).

Une seule instance s'exécute à la fois ; relancer le programme ramène la fenêtre existante au premier plan.

## Configuration

Il n'y a pas de fenêtre de paramètres. 1stChip suit automatiquement Windows :

| Élément | Source |
|---|---|
| Mode clair / sombre | Windows *Paramètres → Personnalisation → Couleurs → Mode d'application* |
| Langue de l'interface | Langue d'affichage de Windows (coréen → coréen, toute autre → anglais) |
| Format de date | Localisé (`yyyy-mm-dd` en coréen, `mm-dd-yyyy` en anglais) |

## Configuration requise

- Windows 10 ou Windows 11, **64 bits**
- Aucun droit d'administrateur requis
- La connexion Internet est facultative — utilisée uniquement pour la vérification des mises à jour de pilotes

## Mises à jour

1stChip **ne** se met **pas** à jour tout seul. Les nouvelles versions sont publiées manuellement après vérification interne et annoncées sur la [page 1stChip](https://v2.kilho.net/1stchip). Consultez l'[avis sur la politique de mise à jour](https://en.kilho.net/archives/notice/2940).

**Historique des versions**

| Version | Date | Notes |
|---|---|---|
| 0.9.0 | 2026-09-18 | Première version |

## Licence

1stChip est un **logiciel gratuit (Freeware)**.

Vous pouvez l'utiliser partout — à la maison, au bureau, dans les écoles et les administrations — et le redistribuer librement sous sa forme non modifiée.

## Liens

- Site web : <https://v2.kilho.net/1stchip>
- Forum : <https://groups.google.com/g/kilhonet>
- X (Twitter) : <https://www.twitter.com/kilhonet>

© KILHO.NET
