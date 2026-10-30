# 💎 ToxicDiamondFarm

**Build Better Minecraft Servers — by ToxicPlugins**

**Version:** 2.0.0 Stable  
**Platform:** Minecraft Java Edition · Paper  
**Java:** 25

ToxicDiamondFarm is a Minecraft Paper plugin that introduces automatic, upgradeable Diamond Generators to your survival server.

Craft your generator, collect diamonds automatically, upgrade its production speed, and build your own diamond empire!

**[⬇️ DOWNLOAD TOXICDIAMONDFARM v2.0.0](https://github.com/ToxicPlugins/ToxicDiamondFarm/releases/tag/v2.0.0)**

---

## ✨ Features

- 💎 **Automatic Diamond Generation** — Generate diamonds while your generator's chunk is loaded.
- ⚙️ **Four Upgrade Levels** — Unlock faster diamond production.
- 🖥️ **Interactive GUI** — Upgrade your generator through a simple menu.
- 📦 **Automatic Storage** — Diamonds are automatically stored in chests or barrels.
- 🔒 **Ownership Protection** — Protect generators from unauthorized breaking.
- 🤝 **Shared Upgrades** — Help other players upgrade their generators using your own materials.
- 💾 **Persistent Data** — Keep generator upgrades across server restarts.
- 🛡️ **Explosion Protection** — Protect generators from TNT.
- 🔧 **Piston Protection** — Prevent unwanted generator movement.
- 📖 **Custom Crafting** — Craft generators using survival materials.
- ⚙️ **Customizable Settings** — Configure production speeds and upgrade requirements.

---

## ⏱️ Generator Levels

Upgrade your Diamond Generator to increase production speed.

- **Level 1:** 1 diamond every 30 minutes
- **Level 2:** 1 diamond every 20 minutes
- **Level 3:** 1 diamond every 10 minutes
- **Level 4:** 1 diamond every 5 minutes

Production intervals can be customized in `config.yml`.

## 🛠️ Crafting Recipe

To craft a Diamond Generator, you need:

- 4x Obsidian
- 2x Diamond Block
- 2x Redstone Block
- 1x Nether Star

Place the materials in a crafting table:

| Obsidian | Diamond Block | Obsidian |
|---|---|---|
| Redstone Block | Nether Star | Redstone Block |
| Obsidian | Diamond Block | Obsidian |

The recipe is automatically unlocked when players join the server.

---

## 📥 Installation

1. Download the latest JAR from the [Releases page](https://github.com/ToxicPlugins/ToxicDiamondFarm/releases/tag/v2.0.0).
2. Stop your Minecraft server.
3. Place `ToxicDiamondFarm-2.0.0.jar` inside your server's `plugins` folder.
4. Start your server.
5. Configure the plugin in `plugins/ToxicDiamondFarm/config.yml`.
6. Enjoy your Diamond Generators!

**Important:** Back up your existing plugin data before updating from an older version.

## 🎮 Commands

**Give a Diamond Generator:**

`/diamondfarm give <player>`

**Reload the configuration:**

`/diamondfarm reload`

Administrative commands require appropriate permissions.

---

## 🖱️ How to Use

**1. Place Your Generator**

Craft or receive a Diamond Generator and place it on the ground.

**2. Add Storage**

Place a chest or barrel directly above the generator.

**3. Collect Diamonds**

Your generator automatically produces diamonds while its chunk is loaded.

**4. Upgrade Your Generator**

Right-click the generator to open the upgrade GUI.

**5. Place Blocks Without Opening the GUI**

Hold Shift and right-click to place a chest or barrel without opening the menu.

**6. Relocate Your Generator**

Break and replace your generator while keeping its upgrade level.

---

## 🔐 Security & Protection

ToxicDiamondFarm includes:

- Ownership-based generator protection
- TNT explosion protection
- Piston movement protection
- Basic duplication safeguards
- Safe handling of full storage containers
- Protection against item loss when storage is missing

These features have been functionally tested, but the plugin has not undergone an independent security audit.

---

## 🖥️ Compatibility

**Verified environment:**

- Minecraft Java Edition 26.2
- Paper 26.2 Build 123
- Java 25

The plugin has been tested on a dedicated Paper test server and a live survival server.

Compatibility with other Minecraft versions and server implementations has not yet been verified.

---

## 📸 Screenshots

Gameplay screenshots showing the generator, crafting recipe, and upgrade GUI will be added soon.

---

## 🐛 Bug Reports & Feedback

Found a bug or have a feature suggestion?

[Report an issue on GitHub](https://github.com/ToxicPlugins/ToxicDiamondFarm/issues)

When reporting a bug, please include your Paper version, plugin version, steps to reproduce the issue, and any relevant console errors.

---

## 👑 About ToxicPlugins

**ToxicPlugins** develops Minecraft server plugins focused on automation, progression, gameplay improvements, and server management.

Our goal is to create powerful and easy-to-use tools that help server owners build better Minecraft experiences.

**Our motto: Build Better Minecraft Servers.**

ToxicDiamondFarm is our first public stable release.

This project was developed with substantial AI assistance and functionally tested by the project creator.

---

**💚 ToxicPlugins — Build Better Minecraft Servers.**

*Not an official Minecraft product. Not approved by or associated with Mojang or Microsoft.*
