# Roblox Lua Script Utility (Discontinued)

> **Status: Archived / Discontinued.** This project is no longer maintained, updated, or supported. It is preserved here for portfolio and reference purposes only.

A client-side Lua scripting utility for Roblox, built as a personal learning project to explore **Lua runtime injection, custom in-game UI development, and reverse-engineering of client-side game logic**. It is not intended for use with any live game or service.

---

## 📖 Overview

This was an early project of mine written in **Luau (Roblox Lua)**. The goal was to understand how client-side scripting environments work in practice — how a script is loaded, executed, and rendered into an overlay UI — and to build a small, self-contained scripting tool from scratch.

It consists of:

- A **lightweight script loader** that accepts and executes user-provided Lua snippets at runtime.
- A **custom UI framework** built on Roblox's `ScreenGui` / `Frame` / `TextButton` APIs, with a draggable window, collapsible sections, and toggleable modules.
- A **module system** for organising and hot-toggling individual features.
- A basic **config/state handler** for persisting toggles between sessions.

---

## 🛠️ Tech Stack

| Area | Details |
|------|---------|
| Language | Luau (Roblox Lua) |
| Runtime | Roblox client environment |
| UI | Roblox `GuiObject` API (ScreenGui, Frame, TextLabel, etc.) |
| Architecture | Modular — loader, UI layer, feature modules, config handler |

---

## ✨ What It Does

- Loads and runs user-supplied Lua at runtime in a sandboxed client context.
- Provides a customisable overlay UI with draggable windows and toggles.
- Supports modular feature registration — new modules can be dropped in and appear in the UI automatically.
- Handles simple config save/load via Roblox's `DataStore`-free local persistence.

---

## 🎯 Why I Built It

This was never a production project — it was a way to learn:

- **Luau / Lua fundamentals** — tables, metatables, closures, coroutines.
- **UI development from scratch** — no frameworks, just raw Roblox GUI APIs.
- **Modular architecture** — separating a loader, a UI layer, and independent feature modules.
- **Client-side runtime behaviour** — how scripts are executed and sandboxed in a game engine.
- **Reverse-engineering & debugging** — understanding how client-side state is represented and modified.

Lessons from this project directly fed into later work on UI tooling and Lua-based automation.

---

## ⚠️ Disclaimer

This project is **discontinued and archived**. It is published **solely for educational and portfolio purposes**, to demonstrate the techniques and architecture described above.

- It is **not maintained**, receives no updates, and should not be expected to function with any current version of Roblox.
- It is **not intended for use in any live game or service**, and using tools like this may violate the terms of service of the platform it was written for.
- The author does not endorse or support using this code to disrupt, gain unfair advantage in, or otherwise interfere with any online service.

If you're interested in the *techniques* (Lua loaders, UI frameworks, module systems), you're welcome to read the code — please don't run it against anything live.

---

## 📦 Repository Notes

- Code is preserved **as-is** from the time it was last worked on.
- No issues, PRs, or support requests will be addressed.
- Dependencies (if any) may no longer be available.

---

## 👤 Author

**[Your Name]**
- GitHub: [@yourhandle](https://github.com/GhostExe-cloud)
- LinkedIn: [Mahlatse Mkabane]

---

*Archived with 🫡 — a learning project from an earlier chapter.*
