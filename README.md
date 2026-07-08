<h1 align="center">IWOSS / iwosw</h1>

<p align="center">
  <b>Systems-heavy game and tooling developer</b><br />
  NeoForge mods, Rust native engines, ESP32 tooling, Godot prototypes, and focused web apps.
</p>

<p align="center">
  <a href="https://github.com/iwosw?tab=repositories">Repositories</a> ·
  <a href="https://github.com/iwosw/nature">Nature</a> ·
  <a href="https://github.com/iwosw/Vivarium-Libera">Vivarium Libera</a> ·
  <a href="https://github.com/iwosw/lumen-et-signum">Lumen et Signum</a> ·
  <a href="https://github.com/iwosw/SafeStep">SafeStep</a>
</p>

---

## About

I build projects where mechanics, persistence, networking, and tooling matter. Most of my work is game-adjacent: Minecraft mods with custom world rules, Rust-backed engines, embedded tooling, and interactive web projects.

- Minecraft modding: NeoForge/Forge, Java 21, registries, mixins, custom payload networking, saved data, data generation, optional mod integrations.
- Game systems: terrain generation, biome logic, entity simulation, agriculture, livestock, combat, quests, progression, saves, and server rules.
- Rust tooling: JNI native libraries, desktop apps, parsers/DSLs, serial protocols, ESP32 firmware, and capability checks.
- Web: React, Vite, TypeScript, static sites, interactive learning tools, and polished UI flows.

## Tech

![Java](https://img.shields.io/badge/Java-21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![NeoForge](https://img.shields.io/badge/NeoForge-1.21.1-orange?style=flat-square)
![Forge](https://img.shields.io/badge/Forge-Modding-orange?style=flat-square)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-333333?style=flat-square&logo=espressif&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Godot](https://img.shields.io/badge/Godot-478CBF?style=flat-square&logo=godotengine&logoColor=white)

## Public Work

### Minecraft And Game Systems

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

## Private And In Progress

Not everything is public yet, but the private work is a big part of what I build.

- Godot 4 mercenary-manager prototype for Yandex Games: a hand-drawn world map, 25+ points of interest, road costs, threat previews, auto-combat, enemy tables, quests, random road events, inventory, equipment sets, hiring, healing, permadeath, prestige, local saves, and prepared Yandex SDK hooks for ads, cloud saves, and leaderboards.
- Minecraft server systems: claims, settlements, war/peace state, Recruits/Workers/JourneyMap integrations, serf/recruit conversion, villager biology, RP names, knowledge sync, food spoilage, custom buffalo behavior, ownership tools, and server-specific gameplay rules.
- Experimental notes and prototypes for shops, websites, and content pipelines.

## Current Focus

- Shipping more complete NeoForge 1.21.1 systems instead of isolated items/blocks.
- Making Java/Rust boundaries safe enough for real gameplay through validation, smoke tests, and compatibility hashes.
- Building simulation-heavy mechanics: terrain, water, seasons, diseases, livestock, settlements, and progression loops.
- Turning prototypes into documented projects with build commands, configs, tests, and clear architecture notes.

## GitHub

- Main public stack: Java, Rust, TypeScript, JavaScript.
- Main private/experimental stack: GDScript, Java, TypeScript.
- Profile: [github.com/iwosw](https://github.com/iwosw)
