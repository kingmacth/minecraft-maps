[中文](README.md) | **English**

# Kids Plaza

A custom Minecraft Bedrock survival map for a group of kids playing together.
You spawn in a safe, lively town plaza: gear, food and tools in the shops are all free to take (**Heidou's treat**), you keep your inventory when you die, and falls do no damage. Outside town there are snowy mountains, an ocean, a farm and plains, and three themed islands to the east waiting to be explored by boat. Every chest on the map restocks itself, so a new group of players always finds full chests.

---

## Basics

| Item | Details |
|---|---|
| Game version | Bedrock Edition 1.21.130+ (Windows / Android / iOS) |
| Mode | Survival (monsters roam outside town at night) |
| Spawn | (3, 70, 6), the centre of the town plaza |
| World file | `KidsPlaza-v3.23.mcworld` |
| Current version | v3.23 |

Kid-friendly rules:

- **Keep inventory on death**: nothing in your backpack is ever lost, so exploring is stress-free
- **No fall damage**: climb mountains and jump off cliffs, it never hurts
- **Coordinates and locator bar**: you can always see where your friends are, so nobody gets lost
- **Monster-safe plaza**: monsters are cleared automatically inside town, and buildings cannot be broken

## What's in the map

### The town (spawn)

- **Plaza**: a blue beacon beam shoots into the sky, with big N / S / E / W letters and signs on the ground so you can always tell directions; a fence ring with gates surrounds it
- **8 houses**: each has a bed and a starter chest by the door (locator map, compass, bread, torches, iron sword, iron pickaxe, bed, oak logs); the barrel beside each house is your personal storage
- **8 shops**: every shop has a real NPC shopkeeper behind the counter — weapons, armour, food, tools, building blocks and more; the goods sit in the stall chest, just open it and take what you need
- **House 1 is Heidou's room**: the host's own room, locked — other players cannot get in

### Auto-restock system

All **25 stocked containers on the map restock automatically**: the shops, house starter chests, 2 plaza resource chests, the farm chest, the fishing chest, the three islands' snack chests, the crypt chest and the underground treasure chest. Once a chest is emptied it refills itself, so whoever plays first or last, every chest is full. The empty barrels by the houses do not restock — they are for storing your own things.

### The land around town

- **North**: snowy mountains, peaks about 111 blocks high, with emerald ore in the rock
- **East**: the ocean — the main pier has a boardwalk and a fishing platform, with 5 boats moored
- **South**: plains and the farm — wheat fields, water channels and a farm chest; walk on the centre plank path so the crops are not trampled; there is a pond nearby
- **West**: hills and forest, where wolves roam (bring bones to tame one into a dog); the hills also hold a lava lake (-170, 75, -60) — scoop lava, pour water over it for obsidian, build a Nether portal, and mine the vanilla path to netherite upgrades for your diamond gear
- **Underground**: solid stone under the whole map, seeded with ores by depth (coal and iron everywhere, gold and redstone mid-depth, diamonds deep down, emeralds only inside the mountains) — and a treasure chest buried under the town

### Three islands (sail east)

| Island | What's there |
|---|---|
| 🌲 Forest Island | A forest of 130 oak trees, with cows, sheep, pigs and chickens grazing |
| 👹 Monster Island | Farther out at sea and about twice the area; resident zombies, skeletons, spiders and creepers, 6 of each; a stone-brick crypt (zombie and skeleton spawners + loot chest) plus 4 open-air spawner altars keep the nights busy |
| ⛏️ Ore Island | A whole island of rock, but the ore (about 20,000 blocks in sampled columns) is buried deep with none visible on the surface; a framed starter shaft with ladders drops you to digging depth |
| ⛏️ Camp Mines | Three framed mine entrances near camp (No.1 at the north foothills, No.2 in the west hills, No.3 on the south plains): ladders down 14 blocks, then you dig yourself |

Each island has a west dock (plank deck, lantern, themed name sign), one boat moored for the trip back, and a snack chest where you land (bread, apples, carrots, a fishing rod, torches).

### Beast Mount Park (west of the farm)

On the southern plains, west of the farm (around -60, 100), a mount park keeps **2 ravagers and 2 polar bears**. A small behavior pack built into the world makes them docile, rideable and faster than horses. Walk up and tap "Ride" to mount; two buttons inside the park also auto-mount the nearest beast. They are safe to ride into town — the plaza's monster protection will not mistake them for wild monsters. Once every mount of a species has been ridden away, the park automatically restocks two fresh ones, just like the chests.

## How to play

### Import

1. Download `KidsPlaza-v3.23.mcworld` from this folder
2. Open the file on Windows / Android / iOS — the game imports it automatically
3. Pick **Kids Plaza 小朋友广场 v3.23** from your world list and play

### First steps

1. You spawn on the plaza — check the direction letters on the ground first
2. Visit any shop and take gear and food from the stall chest (Heidou's treat, take freely)
3. Open the starter chest at a house for a map and compass; store your treasures in the barrel beside the house
4. In the daytime, explore town, work the farm to the south, or fish from the pier to the east
5. For an adventure, sail east from the main pier — each island is different, and every island keeps a boat for the way back

### Tips

- **The front slots of shop chests are restock slots**: take freely, but do not store your own things there — fresh stock will push them out
- When you cannot find your friends, use the **locator bar** at the top of the screen, or meet under the plaza beacon
- The town is safe at night; outside town there are monsters, so travel together after dark
- The ore island is steep on the side facing town — land at its dock

## Version history

- **v3.23** (current): fixed the sugarcane field so the cane actually grows — strict water/cane row alternation (water on both sides, 217 canes) and the regrow template has its own water row; harvested cane is restored within ~30 s
- **v3.22**: new sugarcane field at the foot of the north mountains, irrigated by a stream flowing down the slope; cane makes paper, paper makes firework rockets
- **v3.21**: all in-game text is English only now (signs, chest names, world name); map content unchanged
- **v3.20**: more small animals on the forest island (rabbits!); a 16-tree auto-regrow grove — chopped parts grow back within 30 seconds; the lava lake and underground lava pools refill themselves every 30 seconds
- **v3.19**: Monster Island moved farther out, ~2x area, open-air spawners; ore island ore buried deep + starter shaft; three camp mine entrances; beacon made unbreakable (deny gap plugged)
- **v3.18**: the mount park restocks itself — once every mount of a species has been ridden away, two fresh ones appear
- **v3.17**: new Beast Mount Park — ravagers and polar bears are rideable (a small behavior pack is built into the world file; nothing extra to install)
- **v3.16**: lava added (a lava lake in the west hills + underground lava pools), so the vanilla netherite upgrade path can be mined end to end
- **v3.15**: mainland coastline and strait restored to v3.12; the ore island's west side steepened
- **v3.14**: every chest on the map restocks
- **v3.13**: the three islands enlarged about 4×
- **v3.12**: the islands themed (forest / monster crypt / ore)
- **v3.11**: full shop assortments restored
- **v3**: base version with the town, NPC shopkeepers, terrain and restock system

## Files in this folder

- `KidsPlaza-v3.23.mcworld` — the world file
- `使用说明-KidsPlaza-v3.23.txt` — v3.21 release notes (Chinese)
- `README.md` — this guide in Chinese
- `README_EN.md` — this file (English)
