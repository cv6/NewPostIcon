# [DD] New Post Icon

![Version](https://img.shields.io/badge/version-1.1.1-blue.svg) ![XenForo](https://img.shields.io/badge/XenForo-2.3%2B-orange.svg)

*Read this in other languages: [Deutsch](README.de.md)*

**[DD] New Post Icon** is a specialized UI enhancement for XenForo designed to improve user navigation by visually highlighting new, unread content within thread lists.

---

## 🚀 Key Features in Detail

### 📍 Smart Status Indicators
* **Dynamic Indicator**: Automatically places a visual icon before the title of any unread thread.
* **State Awareness**: The icon is only displayed for threads containing content the specific user hasn't seen yet. It disappears instantly once the thread is marked as read.

### 🎨 Complete Design Control via Style Properties
The add-on is deeply integrated into the XenForo Style system to offer maximum flexibility:
* **Custom Icons**: Choose any icon from the FontAwesome library (e.g., `fa-certificate`, `fa-star`, `fa-bolt`).
* **Style-Specific Customization**: Since settings are stored in Style Properties, you can define different icons or colors for each of your styles (e.g., specific looks for Light vs. Dark themes).
* **Zero CSS Required**: Colors and icon classes are configured directly in the ACP—no manual editing of `extra.less` is necessary.

### ⚡ Performance & Compatibility
* **Lightweight Architecture**: Designed with a minimal footprint to ensure no impact on page load speeds.
* **Seamless Integration**: Uses clean template modifications for `thread_list_macros` to ensure compatibility with other UI add-ons.

---

## ⚙️ Configuration

In your Admin Control Panel, navigate to:
**Styles -> Style Properties -> [DD] New Post Icon**

You can configure the following:
1. **New Post Icon**: Enter the FontAwesome class for your preferred icon.
2. **New Post Icon Color**: Define the icon's color. Supports CSS color names, hex codes, or XenForo style variables (e.g., `@xf-paletteColor3`).

---

## 📋 Requirements

* **XenForo**: 2.3.0 or higher
* **Dependency**: [[DD] Core AddOn](https://forum.dice-dragons.de/) (v1.2.0+)

---

## 🔗 Links & Support

* **Developer**: [Hoffi](https://forum.dice-dragons.de/mitglieder/hoffi.1/)
* **Support**: [Dice Dragons Forum](https://forum.dice-dragons.de/forum/new-post-icon/)