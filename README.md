# Conveyor Belts

Wooden belts that move your items and your creatures for you. Build a small factory and let automation do the hauling.

![The whole farm: boars ride from the pen through the grinder, and the loot is sorted into chests](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/farm.gif)

> Boars fall from their pen onto a belt. The grinder kills them. The loot rides on. The filter sends the leather to one chest, and the link puts the meat into another.

## What is new in 0.2.0

- **Settings windows.** Press E on a link or an item filter to open its settings (see below).
- The item filter holds a list of up to 8 items, families of items (for example all ores) and creatures.
- The link has three modes: In, Out and Both. The modes are only for chests. A machine on a link always only takes items in. You can set how many items it pushes out at a time, and how full it fills a chest or machine.
- Ramps also come without pillars.
- You can build a chest or machine next to a link by aiming at the link's side. Before, it stayed red there.
- The blast furnace drops its bars off its chute, not onto it.
- Items on a belt wait for each other instead of pushing.
- Chests and machines snap only to links now, and the mod no longer changes how anything else snaps.
- Less spam in the log.
- **Old links:** a link built in 0.1.0 now pushes out a full stack at a time, not 1 item per second. To slow it down, set its push size.

## The pieces

Build them all with the hammer, in the **Misc** tab.

| | Piece | What it does |
|:--|:--|:--|
| ![Belt](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/belt.gif) | **Belt** | Carries items and creatures. Comes 1 m, 2 m and 4 m long, as a left or right corner, and as a ramp up or down, with or without pillars. |
| ![Drop floor](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/drop-floor.gif) | **Drop floor** | A floor that lets only grown creatures fall through (or only young ones). |
| ![Grinder](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/grinder.gif) | **Grinder** | Kills every creature that rides in. The loot rides on. Do not stand in it! |
| ![Item filter](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/item-filter.gif) | **Item filter** | Sends the items and creatures on its list to the side. Everything else goes straight on. Press E to pick items, families of items and creatures. |
| ![Link](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/link.gif) | **Link** | Puts items into a smelter, kiln, windmill, spinning wheel or chest. It can also take items out of a chest. Press E to set its mode and how many items it moves. |
| ![Trash box and trash bin](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/trash.gif) | **Trash box** | Snaps onto a link. Deletes what the chests and machines cannot take. |
| | **Trash bin** | Put it at the end of a belt. Items that fall in are gone. |
| ![Power mill and rope-drive post](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/power.gif) | **Power mill** | A small windmill that makes power for the other pieces. |
| | **Rope-drive post** | Carries power over a gap, with a rope to another post. |

## Settings windows

Press E on a link or an item filter to open its settings.

<p>
<img src="https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/link-window.png" height="320" alt="The link's settings window: mode Both, a push of 10 items, a fill limit of 200 of each kind">
<img src="https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/filter-window.png" height="320" alt="The item filter's settings window: Ores, Raw meat, Boar and Leather Scraps on the list">
</p>

## Power

Every belt, filter, grinder and link needs power from a **power mill**. Pieces that touch share the power. If there is not enough, they stop. Look at a piece to see why it stopped. Walls and a roof round a mill make it weaker.

## Playing with friends

Everyone must have the mod: every player and the server.

## Install

Use a mod manager (r2modman, Gale or Thunderstore Mod Manager). It installs **BepInEx** and **Jotunn** for you.

## Settings

The costs, the power numbers and the rope length can be changed in the config file. On a server, only an admin can change them.

Each player can also turn off `[Building] SnapToLinks`. Then chests and machines no longer snap to links.

<details>
<summary>Costs and power</summary>

| Piece | Cost | Power |
|:--|:--|:--|
| Belt 1 m / 2 m / 4 m | Wood 3/6/12, Resin 1/2/4 | 0.5 / 1 / 2 |
| Corner, ramp | Wood 6, Resin 2 | 1 |
| Drop floor | Wood 6, Resin 2 | 1 for all tiles that touch |
| Item filter | Wood 8, Resin 2 | 2 |
| Grinder | Wood 10, Stone 10, Resin 2 | 8 |
| Link | Wood 8, Stone 12, Resin 2 | 3 |
| Trash box | Wood 4, Resin 1 | 0 |
| Trash bin | Wood 8, Resin 2 | 0 |
| Power mill | Wood 20, Resin 2, Leather scraps 2 | gives 20 |
| Rope-drive post | Wood 8, Resin 1 | 0 (rope up to 16 m) |

</details>

## Made with AI

This mod was written with the help of an AI (Claude).
