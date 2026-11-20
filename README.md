<div align="center">

<img src=".github/logo.svg" width="96" alt="Logo de Bobine">

# Bobine

**Un éditeur vidéo qui tourne sur ton ordinateur.**

Montage, export et transcription gratuits en local, sans compte.<br>
L'agent IA se paie au quota, et un quota vide ne bloque jamais ton montage.

[![Dernière version](https://img.shields.io/github/v/release/evanosm/bobine-releases?style=flat-square&label=version&color=FF2E48)](https://github.com/evanosm/bobine-releases/releases/latest)
[![Téléchargements](https://img.shields.io/github/downloads/evanosm/bobine-releases/total?style=flat-square&label=t%C3%A9l%C3%A9chargements&color=1f1f1f)](https://github.com/evanosm/bobine-releases/releases)
![macOS, Windows, Linux](https://img.shields.io/badge/macOS%20%C2%B7%20Windows%20%C2%B7%20Linux-1f1f1f?style=flat-square)

### [Télécharger la dernière version →](https://github.com/evanosm/bobine-releases/releases/latest)

</div>

<br>

## Installer

| Système | Fichier à prendre | Version minimale |
| :-- | :-- | :-- |
| **macOS** (Apple Silicon) | `Bobine_<version>_aarch64.dmg` | macOS 12 |
| **Windows** (64 bits) | `Bobine_<version>_x64-setup.exe` | Windows 10 |
| **Linux** (x86_64) | `Bobine_<version>_amd64.AppImage` ou `.deb` | |

Une fois installée, Bobine se met à jour toute seule : elle vérifie les nouvelles versions au
lancement et te propose de redémarrer. Chaque mise à jour est signée, et l'app refuse un fichier
dont la signature ne correspond pas.

## Ce que fait Bobine

- **Monter vite.** Timeline multi-pistes, coupes au clavier, transitions, vitesse, fondus, keyframes.
- **Travailler à partir du texte.** Transcription locale (Whisper), recherche dans ce qui est dit,
  suppression des silences en un geste.
- **Sous-titrer.** Sous-titres générés depuis la transcription, styles animés mot à mot,
  export SRT, VTT et ASS.
- **Soigner l'image et le son.** Effets, correction colorimétrique, LUT, réduction de bruit,
  égaliseur, table de mixage, normalisation du volume à l'export.
- **Demander à l'agent.** Décris ce que tu veux, il prépare les modifications et te les montre :
  tu appliques ou tu annules. Tout reste annulable.
- **Brancher ta propre IA.** Un serveur MCP local permet à Claude Desktop ou à un autre client
  de piloter ton montage.

Ta vidéo ne quitte pas ta machine : lecture, rendu, transcription et export tournent en local.

## Canal bêta

Les testeurs qui veulent les nouveautés avant tout le monde peuvent activer le canal bêta dans
les réglages de l'app. Les versions bêta sont publiées sous
[`beta-channel`](https://github.com/evanosm/bobine-releases/releases/tag/beta-channel).

## Un problème, une idée ?

Dans l'app : menu **Aide › Envoyer un retour…**. L'app te montre tout ce qui part avec ton
message (version, système, fin du journal) avant l'envoi.

Sinon, ouvre une [issue](https://github.com/evanosm/bobine-releases/issues/new?labels=retour).

<br>

<div align="center">
<sub>Ce dépôt ne contient que les versions publiées (binaires signés et <code>latest.json</code>, lu par les mises à jour automatiques). Le code source est privé.</sub>
</div>
