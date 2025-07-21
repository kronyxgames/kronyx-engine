# 🌀 Kronyx Engine

**Kronyx Engine** is an open-source, modular and high-performance game engine developed by [Kronyx Games Studios](https://kronyxgames.com), a division of [Sky Genesis Enterprise](https://skygenesisenterprise.com). Based on the robust foundation of [Bevy Engine](https://bevyengine.org) and written in Rust, Kronyx Engine is designed to power the next generation of multi-platform games, immersive animations, and interactive simulations.

## 🚀 Vision

We built Kronyx Engine to be:
- 🔓 **Open-source by design**
- 🎮 **Cross-platform and future-proof** (PC, consoles, handhelds, web)
- 💡 **Modular and scalable** for 2D/3D games, transmedia worlds, and real-time animation
- 🔧 **Developer-friendly** with fast iteration and modern tools
- 🌐 **Integrated into a wider ecosystem** (Kronyx ID, store, tools, SDKs)

Whether you're developing a tactical MMO, a narrative-driven platformer, or a stylized animated series — Kronyx Engine provides the flexibility and power to create, iterate, and expand.

---

## ✨ Key Features

- 🧠 **ECS-based Architecture**: Powered by a modern Entity Component System (ECS) for clean, efficient logic separation.
- 🖼️ **2D & 3D Rendering**: Modern rendering pipeline using WGPU for high performance and portability.
- 🔊 **Audio System**: Robust and extensible sound framework with spatial audio and music cue support.
- 🎨 **Animation Framework**: Ready for both in-game and cinematic animations (for use in animated content pipelines).
- 📦 **Plugin System**: Add or remove systems easily through modular plugins.
- 🕹️ **Input Abstraction**: Unified input for keyboard, mouse, gamepads, and custom devices.
- 🌍 **Localization-Ready**: Built-in support for i18n for global-ready titles.
- 🔌 **APIs & Integrations**: Future support for Kronyx Cloud Services, Kronyx ID, asset stores, and modding APIs.

---

## 🔧 Requirements

- **Rust** 1.75+ (use [rustup.rs](https://rustup.rs))
- Target OS: Linux, Windows, macOS
- Optional: WebAssembly target for browser deployment

```bash
# Install Rust
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
````

---

## 🛠️ Getting Started

```bash
# Clone the repository
git clone https://github.com/kronyxgames/kronyx-engine.git
cd kronyx-engine

# Run an example
cargo run --example basic_scene
```

More demos and templates will be added under `/examples`.

---

## 📁 Directory Structure

```
kronyx-engine/
├── crates/            # Engine core modules
├── examples/          # Starter examples and demos
├── assets/            # Built-in test assets (replaceable)
├── docs/              # Engine documentation (markdown or mdBook)
└── tools/             # Internal tools, exporters, CLI
```

---

## 🧩 Planned Modules

* `kronyx_networking` — multiplayer framework
* `kronyx_ai` — behavior trees, utility AI, procedural logic
* `kronyx_cinematics` — advanced cutscene & animation tools
* `kronyx_editor` — visual editor (GUI-based, WIP)
* `kronyx_console` — integration layer for KronyxOS & handheld devices

---

## 🌍 Open-Source Philosophy

Kronyx Engine is fully open-source and community-driven. You’re free to:

* Fork, extend, and modify
* Use in commercial and open projects
* Contribute via pull requests, discussions, and issues

> All code is licensed under **MIT license** for maximum compatibility.

---

## 🤝 Contributing

We welcome contributors of all kinds: developers, artists, writers, and testers.

👉 See our [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines
👉 Join our Discord: [discord.gg/kronyx](https://discord.gg/kronyx)
👉 Talk to us via [issues](https://github.com/kronyxgames/kronyx-engine/issues) or [Discussions](https://github.com/kronyxgames/kronyx-engine/discussions)

---

## 📚 Documentation

We're building detailed docs with guides, tutorials, and API references here:

📘 [Wiki](https://wiki.kronyxgames.com) *(coming soon)*

---

## 🔒 Licensing & IP

All engine code is released under open-source licenses.
Games built with Kronyx Engine are fully yours — your IP, your business.

For the Kronyx IP itself (our internal games, universes, and characters), we maintain a separate copyright.

---

## 🧠 Credits

Kronyx Engine is built with:

* ❤️ [Bevy Engine](https://bevyengine.org) (Rust-based game engine)
* 🦀 Rust and the amazing OSS ecosystem
* ☁️ Supported by [Sky Genesis Enterprise](https://skygenesisenterprise.com)

---

## 📬 Contact & Links

* 🌐 Website: [https://kronyxgames.com](https://kronyxgames.com)
* 💬 Discord: [discord.gg/kronyx](https://discord.gg/kronyx)
* 🛠️ GitHub Org: [github.com/kronyxgames](https://github.com/kronyxgames)

---

> *Build the future of games. Together. — Kronyx Games Studios*