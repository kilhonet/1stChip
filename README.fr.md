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

1. Lancez `1stChip.exe`. La liste du matériel s'affiche immédiatement.
2. Chaque catégorie présente ses périphériques ; la première ligne est le périphérique représentatif, les autres sont affichés en gris.
3. Sous le nom de chaque périphérique figurent la version et la date du pilote **installé**.
4. Une marque jaune `!` à côté d'un périphérique signifie l'un des cas suivants :
   - aucun pilote n'est installé,
   - le périphérique signale un code de problème, ou
   - un pilote plus récent est connu — survolez pour voir la version.
5. **Cliquez** sur la marque `!` pour ouvrir dans votre navigateur la page du pilote de ce périphérique.
6. Le panneau du bas affiche la fréquence du processeur, la taille de la mémoire et le système d'exploitation.

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
