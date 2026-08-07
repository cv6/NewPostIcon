# [DD] New Post Icon
*Diese Dokumentation ist auch verfügbar auf: [English](README.md)*

![Version](https://img.shields.io/badge/version-1.1.2-blue.svg) ![XenForo](https://img.shields.io/badge/XenForo-2.3%2B-orange.svg) ![PHP](https://img.shields.io/badge/PHP-8.2%2B-qt.svg)

[DD] New Post Icon ist ein spezialisiertes UI-Tool für XenForo, das die Benutzererfahrung verbessert, indem es neue, ungelesene Inhalte in Themenlisten visuell deutlich hervorhebt.

---

## Features / Funktionen
* Intelligente Status-Markierung: Fügt automatisch ein visuelles Indikator-Icon vor dem Titel jedes ungelesenen Themas ein.
* Echtzeit-Aktualisierung: Das Icon erscheint nur für Themen mit Inhalten, die der jeweilige Benutzer noch nicht gesehen hat. Sobald ein Thema gelesen wurde, wird das Icon ausgeblendet.
* Freie Icon-Wahl: Wähle ein beliebiges Icon aus der FontAwesome-Bibliothek (z. B. fa-certificate, fa-star, fa-bullseye).
* Stylespezifisches Styling: Da die Einstellungen in den Style-Properties liegen, kannst du für jeden Style (z. B. Light Mode / Dark Mode) unterschiedliche Icons oder Farben definieren.
* Kein CSS nötig: Farben und Icon-Klassen werden direkt im ACP konfiguriert, manuelle Änderungen an der extra.less sind nicht erforderlich.
* Minimalistischer Footprint: Das Add-on ist extrem leichtgewichtig und beeinträchtigt die Ladezeit der Themenliste nicht merkbar.
* Saubere Integration: Nutzt präzise Template-Modifikationen für die thread_list_macros, um maximale Kompatibilität mit anderen Add-ons zu gewährleisten.

---

## Requirements / Voraussetzungen
* XenForo: 2.3.0+
* PHP: 8.2.0+
* Dependency: [DD] Core AddOn (v1.4.2+)

---

## Installation
### 1. Upload
Lade den Inhalt des upload-Ordners in dein XenForo-Hauptverzeichnis hoch.

### 2. Installation (CLI & AdminCP)
Installiere das Add-on via CLI oder ACP:
```bash
php cmd.php xf:addon-install cv6/NewPostIcon
```

---

## Setup & Configuration / Einrichtung
Navigiere im Administrationsbereich zu:
Styles -> Style-Einstellungen -> [DD] New Post Icon

Dort stehen dir folgende Optionen zur Verfügung:
1. New Post Icon: Die FontAwesome-Klasse für das Icon.
2. New Post Icon Farbe: Die Farbe des Icons. Du kannst CSS-Farbnamen, Hex-Codes oder XenForo-Style-Variablen (wie @xf-linkColor) verwenden.

---

## Links & Support
* Entwickler: [Hoffi](https://forum.dice-dragons.de/mitglieder/hoffi.1/)
* Support Forum: [Dice Dragons Forum](https://forum.dice-dragons.de/forum/new-post-icon/)
* FAQ & XenForo Resource: [FAQ](https://forum.dice-dragons.de/downloads/new-post-icon.150/)
* Spenden: [Amazon Wunschliste](https://www.amazon.de/hz/wishlist/ls/2XPAE7B75LB9T?ref_=wl_share)