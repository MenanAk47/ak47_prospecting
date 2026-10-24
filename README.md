**The ultimate metal detecting and treasure prospecting experience for FiveM servers.** ak47_prospecting introduces an immersive, fully interactive outdoor activity where players equip a custom 3D metal detector to sweep the terrain and unearth valuable underground relics. Featuring realistic proximity-based radar audio beeps, on-the-fly scroll wheel volume controls, shovel excavation scenarios, and an integrated pawn shop economy, it brings engaging exploration and progression to your server. Seamlessly powered by ak47_lib with synchronized multiplayer zones and out-of-the-box support for ESX, QBCore, and QBX.

---

## 🎥 Showcase
<img width="1920" height="1080" alt="thumbnail" src="https://github.com/user-attachments/assets/f35ab757-beff-44e5-9314-a70c904a046c" />

> **[Click here to watch the full feature showcase on YouTube](https://youtu.be/9i9G56x7YL4)**

---


## 🔥 Key Features

Designed to improve roleplay immersion and economy balancing:

### 🔍 Metal Detector & Dynamic Audio Radar

* **Custom 3D Prop & Sweeping Animations:** Equipping the metal detector attaches a custom 3D scanner model (`w_am_digiscanner`) to the player's hands with authentic body posture and sweeping animations.
* **4-Stage Proximity Audio:** Integrated NUI Howler audio plays realistic beep tones that accelerate through 4 distinct frequency tiers as players get closer to buried treasure (<10m, <5m, <2m).
* **On-the-Fly Volume Controls:** Players can smoothly increase or decrease the scanner audio volume at any time using their mouse scroll wheel (`SCROLLUP` / `SCROLLDOWN`) guided by an on-screen controls HUD.

### 🗺️ Prospecting Zones & Dynamic Spawning

* **Configurable Zones & Radius Blips:** Create multiple prospecting areas with custom coordinates, radius circles, spawn limits, and map blip styles directly in the config.
* **Ground-Level Height Calculation:** Buried treasure points automatically calculate accurate ground surface coordinates (`GetGroundZFor_3dCoord`), ensuring realistic placement across hills, dunes, and beaches.
* **GlobalState Multiplayer Sync:** Active search coordinates are managed via FiveM's `GlobalState.searchPoints`, ensuring synchronized zones and preventing duplicate spawns across players.

### ⛏️ Shovel Excavation & Tiered Loot Drops

* **Excavation Scenario & Progress Bar:** Getting within 2 meters triggers a clean `[E] Dig` prompt, putting away the detector to initiate a gardening/digging animation and progress bar.
* **3-Tier Rarity System:** Rewards roll on configurable drop chances divided into Common (100%), Rare (50%), and Epic (10%) loot tiers with randomized quantity ranges.
* **11 Pre-Configured Relics & Valuables:** Comes loaded with items including broken glasses, pendrives, rusted rods, broken phones, action cams, rusty guns, wedding rings, gold chains, gold Rolex watches, diamond necklaces, and rare gemstones.

### 💰 Integrated Pawn Shop Economy

* **Pawn Shop Locations & Blips:** Set up pawn shops with custom map blips and 3D floating world text where players can turn their discoveries into cash.
* **Interactive Sell Menu:** Context menu automatically detects prospecting items in the player's inventory, showing current market prices, held counts, and a custom quantity sell dialog.
* **Dynamic Fluctuating Prices:** Configure items to use fixed prices or randomize between minimum and maximum values on every server restart for a fluctuating roleplay economy.

### 🛠️ Technical Excellence

* **Multi-Framework & Target Support:** Seamlessly works with ESX, QB, QBX, and various target systems (ox_target, qb-target, qtarget).
* **Highly Secure:** Built-in server-side exploit checks, including distance validation and trigger authentication, to prevent cheating.
* **Turnkey Setup & Assets:** Includes complete item definitions for QBCore (`qb.lua`), ox_inventory (`ox.lua`), and ESX SQL (`esx.sql`) alongside custom PNG item icons.

---

## 💻 Framework:

* ESX, QB, QBX

---

## ⚙️ Dependencies:

* ak47_lib: https://github.com/MenanAk47/ak47_lib/releases/latest

---

## ⚙️ How To Install:

* Download ak47_prospecting from your cfx portal.
* Add the script in your resources folder.
* Add items based on your framework instruction.
* Add item images into inventory.
* Start the script in your server.cfg below framework files.
* Make sure you have all dependencies.
* Restart the server.

---

## 🔗 Links & Support:

* **📖 Documentation:** [https://docs.menanak47.com/multi-framework/ak47_prospecting](https://docs.menanak47.com/multi-framework/ak47_prospecting)
* **🛒 Buy Now (Tebex):** [https://menanak47.tebex.io/package/5511571](https://menanak47.tebex.io/package/5511571)
* **💬 Discord Support:** [https://discord.gg/menanak47](https://discord.gg/menanak47)

---

## 📝 Note:
* We don't support custom framework. Make sure you are using official framework update.
* Renaming the script is not allowed. It may break the functionalities.
* Don't upload the script with FileZilla, Use Winscp if you are using FTP for file uploading
