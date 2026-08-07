# [DD] New Post Icon
*This documentation is also available in: [Deutsch](README.de.md)*

![Version](https://img.shields.io/badge/version-1.1.2-blue.svg) ![XenForo](https://img.shields.io/badge/XenForo-2.3%2B-orange.svg) ![PHP](https://img.shields.io/badge/PHP-8.2%2B-qt.svg)

[DD] New Post Icon is a specialized UI enhancement for XenForo designed to improve user navigation by visually highlighting new, unread content within thread lists.

---

## Features / Funktionen
* Smart Status Indicators: Automatically places a visual icon before the title of any unread thread.
* State Awareness: The icon is only displayed for threads containing content the specific user hasn't seen yet.
* Custom Icons: Choose any icon from the FontAwesome library (e.g., fa-certificate, fa-star, fa-bolt).
* Style-Specific Customization: Define different icons or colors for each of your styles (e.g., specific looks for Light vs. Dark themes).
* Zero CSS Required: Colors and icon classes are configured directly in the ACP—no manual editing of extra.less is necessary.
* Lightweight Architecture: Designed with a minimal footprint to ensure no impact on page load speeds.
* Seamless Integration: Uses clean template modifications for thread_list_macros to ensure compatibility with other UI add-ons.

---

## Requirements / Voraussetzungen
* XenForo: 2.3.0+
* PHP: 8.2.0+
* Dependency: [DD] Core AddOn (v1.4.2+)

---

## Installation
### 1. Upload
Upload the contents of the upload folder to your XenForo root directory.

### 2. Installation (CLI & AdminCP)
Install the add-on via CLI or AdminCP:
```bash
php cmd.php xf:addon-install cv6/NewPostIcon
```

---

## Setup & Configuration / Einrichtung
In your Admin Control Panel, navigate to:
Styles -> Style Properties -> [DD] New Post Icon

You can configure the following:
1. New Post Icon: Enter the FontAwesome class for your preferred icon.
2. New Post Icon Color: Define the icon's color. Supports CSS color names, hex codes, or XenForo style variables (e.g., @xf-paletteColor3).

---

## Links & Support
* Developer: [Hoffi](https://forum.dice-dragons.de/mitglieder/hoffi.1/)
* Support Forum: [Dice Dragons Forum](https://forum.dice-dragons.de/forum/new-post-icon/)
* FAQ & XenForo Resource: [FAQ](https://forum.dice-dragons.de/downloads/new-post-icon.150/)