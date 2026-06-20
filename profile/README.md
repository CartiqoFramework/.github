<div align="center">

<img src="https://avatars.githubusercontent.com/u/215322618?s=120&v=4" width="80" style="border-radius: 12px;" />

# CɅRTIQO. FRAMEWORK

**A TypeScript-first foundation for Discord bots, FiveM scripts, and automation systems.**

[![TypeScript](https://img.shields.io/badge/TypeScript-5+-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Platform](https://img.shields.io/badge/Platform-Discord%20%7C%20FiveM-5865F2?style=flat-square&logo=discord&logoColor=white)](https://cartiqo.xyz)
[![License](https://img.shields.io/badge/License-MIT-22c55e?style=flat-square)](LICENSE)
[![Discord](https://img.shields.io/discord/1044098950455627867?color=5865F2&label=Discord&logo=discord&logoColor=white&style=flat-square)](https://discord.gg/8p2xHjsgZ3)

[cartiqo.xyz](https://cartiqo.xyz) · [Join Discord](https://discord.gg/8p2xHjsgZ3) · [Browse Repos](https://github.com/orgs/CartiqoFramework/repositories)

</div>

---

## What is CɅRTIQO?

CɅRTIQO is a modular, developer-friendly framework for building production-ready bots and game scripts without the usual boilerplate mess. Every package is written in strongly typed TypeScript (or Lua where FiveM requires it) and designed to slot together cleanly — you pick what you need and leave the rest.

The goal: make bot and script development **structured, fast, and actually enjoyable**.

---

## Packages

| Repository | Description | Status |
|---|---|---|
| [**CTQCore**](https://github.com/CartiqoFramework/CTQCore) | Core FiveM resource — connection queue, config layer, built on CTQBridge | ⚠️ In development |
| [**CTQBridge**](https://github.com/CartiqoFramework/CTQBridge) | Connects your FiveM server to the CARTIQO dashboard. Kick, ban, and manage players with QBCore, Qbox, ESX, or standalone support | ⚠️ In development |
| [**CTQui**](https://github.com/CartiqoFramework/CTQui) | Modern NUI kit for FiveM — notifications, text UI, progress bars, and more | ⚠️ In development |

> ⚠️ All packages are currently **untested / not production-ready**. Use in staging environments only and expect breaking changes.

---

## Tech Stack

| Layer | Technologies |
|---|---|
| **Languages** | TypeScript, Lua, JavaScript |
| **Runtime** | Node.js |
| **Databases** | Prisma · MySQL · MongoDB |
| **Frameworks** | Discord.js · QBCore · ESX · Qbox |
| **Tooling** | ESLint · Prettier · GitHub Actions |

---

## Design Principles

- **Type-safe by default** — TypeScript throughout, so errors surface at compile time, not runtime.
- **Modular architecture** — each package does one job. Combine what you need; ignore what you don't.
- **Plugin-friendly** — extend core behaviour without touching core code.
- **Lightweight utilities** — no bloated dependencies. Helpers for databases, events, and APIs only when they earn their place.
- **Production-oriented** — config validation, structured logging, and permission layers built in from the start.

---

## Getting Started

Each package has its own setup guide in its repository. Start with the one that fits your use case:

- **Building for FiveM?** → Start with [CTQBridge](https://github.com/CartiqoFramework/CTQBridge), then layer in [CTQCore](https://github.com/CartiqoFramework/CTQCore) and [CTQui](https://github.com/CartiqoFramework/CTQui).
- **Need a CARTIQO dashboard connection?** → CTQBridge handles the server ↔ dashboard link for player management.
- **Want a UI kit for your FiveM scripts?** → CTQui gives you ready-made notifications, progress bars, and text UI components.

---

## Contributing

Pull requests are welcome. If you find a bug, open an issue first so we can align on the fix before you write code.

1. Fork the relevant repository.
2. Create a feature branch: `git checkout -b feat/your-feature`
3. Commit your changes with a clear message.
4. Open a pull request against `main`.

---

## Community & Support

Got questions? Want to share what you're building, or contribute ideas?

**[Join the CɅRTIQO Discord →](https://discord.gg/wh2UVKdC3h)**

You can also reach us directly at [duckodas@gmail.com](mailto:duckodas@gmail.com).

---

## License

All CɅRTIQO repositories are licensed under the **[MIT License](LICENSE)** unless stated otherwise in the individual repo.

---

<div align="center">

*"Build powerful systems. The smart way."*

</div>
