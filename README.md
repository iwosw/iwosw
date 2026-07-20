<h1 align="center">IWOSS / iwosw</h1>

<p align="center">
  <b>Systems-heavy game and tooling developer</b><br />
  NeoForge and Forge mods, Rust native engines, ESP32 tooling, Godot prototypes, and focused web apps.
</p>

<p align="center">
  <a href="https://github.com/iwosw?tab=repositories">Repositories</a> ·
  <a href="https://github.com/iwosw/consilium-regum">Consilium Regum</a> ·
  <a href="https://github.com/iwosw/recruits-use-boomsticks">Recruits Use Boomsticks</a> ·
  <a href="https://github.com/iwosw/nature">Nature</a> ·
  <a href="https://github.com/iwosw/Vivarium-Libera">Vivarium Libera</a> ·
  <a href="https://github.com/iwosw/lumen-et-signum">Lumen et Signum</a> ·
  <a href="https://github.com/iwosw/SafeStep">SafeStep</a>
</p>

<p align="center">
  <a href="https://t.me/IW0SS"><img src="https://img.shields.io/badge/Telegram-%40IW0SS-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
  <a href="https://steamcommunity.com/profiles/76561199230971005/"><img src="https://img.shields.io/badge/Steam-Profile-000000?style=for-the-badge&logo=steam&logoColor=white" alt="Steam" /></a>
  <a href="https://open.spotify.com/user/31aso7loopehipn6lrry4qaigimu"><img src="https://img.shields.io/badge/Spotify-Profile-1DB954?style=for-the-badge&logo=spotify&logoColor=white" alt="Spotify" /></a>
  <img src="https://img.shields.io/badge/Discord-iw0ss-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord: iw0ss" />
</p>

---

## About

I build projects where mechanics, persistence, networking, and tooling matter. Most of my work is game-adjacent: Minecraft mods with custom world rules, Rust-backed engines, embedded tooling, and interactive web projects.

- Minecraft modding: NeoForge/Forge, Java 21, registries, mixins, custom payload networking, saved data, data generation, optional mod integrations.
- Game systems: terrain generation, biome logic, entity simulation, AI control layers, agriculture, livestock, combat, quests, progression, saves, and server rules.
- Rust tooling: JNI native libraries, desktop apps, parsers/DSLs, serial protocols, ESP32 firmware, and capability checks.
- Web: React, Vite, TypeScript, static sites, interactive learning tools, and polished UI flows.

## Tech

![Java](https://img.shields.io/badge/Java-21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![NeoForge](https://img.shields.io/badge/NeoForge-1.21.1-orange?style=flat-square)
![Forge](https://img.shields.io/badge/Forge-Modding-orange?style=flat-square)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C%23](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-333333?style=flat-square&logo=espressif&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Godot](https://img.shields.io/badge/Godot-478CBF?style=flat-square&logo=godotengine&logoColor=white)

## Pulse

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=iwosw&theme=tokyonight" alt="GitHub profile summary" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=iwosw&theme=tokyo-night&hide_border=true&radius=12" alt="Contribution activity graph" />
</p>
## Public Work

### AI And Runtime Tools

[**Consilium Regum**](https://github.com/iwosw/consilium-regum)  
Experimental AI control layer for WorldBox built with Python and C#. It reads save/autosave/live runtime state, generates ruler and unit decisions through local or remote LLMs with heuristic fallback, validates dry-run apply plans, exports guarded runtime sidecars, and uses a BepInEx plugin with fail-closed safety gates before live mutation.

### Minecraft And Game Systems

[**Recruits Use Boomsticks**](https://github.com/iwosw/recruits-use-boomsticks)<br />
Forge 1.20.1 compatibility mod that lets Villager Recruits crossbowmen use Medieval Boomsticks firearms and the heavy crossbow. It includes weapon adapters, ammunition and reload handling, mounted behavior, allied-unit friendly-fire protection, configuration, dedicated-server GameTests, CI, and release-ready documentation.

[**BannerMod**](https://github.com/iwosw/mb-check-class)<br />
Forge 1.20.1 multiplayer kingdom sandbox that unifies settlements, workers, claims, political states, armies, formations, logistics, trade, sieges, and regulated wars. The public repository tracks the active `bannermod` runtime, multiplayer guides, developer status, validation stages, and a structured unfinished-work backlog.

[**Nature**](https://github.com/iwosw/nature)  
NeoForge 1.21.1 terrain-generation mod backed by Rust through JNI. It has native ABI/layout/algorithm validation, packaged native smoke tests, Java/Rust compatibility checks, generated water provenance, biome climate sampling, wind/current queries, client sync payloads, and a GitHub Actions matrix for Linux, Windows, macOS x86_64, and macOS aarch64 builds.

[**Vivarium Libera**](https://github.com/iwosw/Vivarium-Libera)  
Large nature/content mod for Minecraft 1.21.1: plants, herbalist tools, block entities, a herbalist book UI, plum wood set, decorative jars, stream worldgen, localization, GeckoLib, Farmer's Delight integration, JEI dev integration, common tags, data maps, recipes, loot tables, models, and datagen providers.

[**Cultio**](https://github.com/iwosw/cultio)  
Agriculture overhaul with seasonal growth, regional planting rules, crop diseases, crop rotation, weeds, ash-treated farmland, infected animal feed, Serene Seasons integration through reflection, saved field data, an in-game guide, and GameTests for infection mechanics.

[**Animalis Agricultura**](https://github.com/iwosw/animalis-agricultura)  
Livestock simulation mod: sex assignment, pregnancy, litters, nests, feeders, cow lactation, manure, inspection overlays, inherited coat variants, server config rules, custom payload networking, and renderer mixins for visual variants.

[**Caelum**](https://github.com/iwosw/caelum)  
Forge server-side world-integrity tool for skybase/platform detection, delayed stability scanning, illegal fluid cleanup, persistent pending checks, commands, config, player notifications, debug particles, and webhook alerts.

### Rust And Embedded Tooling

[**Lumen et Signum**](https://github.com/iwosw/lumen-et-signum)  
Rust desktop control panel and companion ESP32 firmware. It includes serial/USB port discovery, `espflash` integration, UART monitor, firmware capability negotiation, strict ok/err command execution, and EspScript: a small typed DSL with variables, functions, repeat blocks, timers, board events, formatter, lint warnings, GPIO safety checks, and UART compilation.

### Web And Study Tools

[**SafeStep**](https://github.com/iwosw/SafeStep)  
React/Vite/TypeScript digital-hygiene hub with routes, animated page transitions, articles, a quiz, phishing trainer, privacy/profile simulation tools, theme switching, and security-focused interactive modules.

[**Unified-State-Exam-CS**](https://github.com/iwosw/Unified-State-Exam-CS)  
Static study site for Russian CS exam practice with tasks 1-27, short algorithms, code templates, search, SVG assets, and GitHub Pages deployment.

## Currently Building

- A Godot 4 mercenary-manager prototype for Yandex Games with exploration, quests, progression, and permadeath.
- Minecraft server systems centered on settlements, claims, regulated wars, AI units, and mod integrations.
- Experimental commerce, web, and content-pipeline prototypes.
## Current Focus

- Shipping focused compatibility work with tests, clear version contracts, and release-ready documentation.
- Shipping more complete NeoForge 1.21.1 systems instead of isolated items/blocks.
- Making Java/Rust boundaries safe enough for real gameplay through validation, smoke tests, and compatibility hashes.
- Building simulation-heavy mechanics: terrain, water, seasons, diseases, livestock, settlements, and progression loops.
- Turning prototypes into documented projects with build commands, configs, tests, and clear architecture notes.

## GitHub

- Main public stack: Java, Python, C#, Rust, TypeScript, JavaScript.
- Main private/experimental stack: GDScript, Java, TypeScript.
- Profile: [github.com/iwosw](https://github.com/iwosw)

---

<p align="center">
  <i>«Взял GT-63, мне нужно ехать быстро.»</i><br />
  <sub>- IWOSS</sub><br />
  <br />
  <sub>or</sub><br />
  <br />
  <i>"Close my eyes feel a silhouette over me, all over me."</i><br />
  <sub>- IWOSS</sub>
</p>
