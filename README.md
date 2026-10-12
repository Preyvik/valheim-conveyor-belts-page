# Conveyor Belts

Wooden belts that move your items and your creatures for you. Build a small factory and let automation do the hauling.

![The whole farm: boars ride from the pen through the grinder, and the loot is sorted into chests](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/farm.gif)

> Boars fall from their pen onto a belt. The grinder kills them. The loot rides on. The filter sends the leather to one chest, and the link puts the meat into another.

## What is new in 0.6.0

![Raw meat rides into the kitchen link, the greydwarf chef puts it over the fire and takes it off cooked, and it rides on](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/kitchen-link.gif)

- **Kitchen link.** A greydwarf chef runs a cooking station, iron cooking station, oven or fermenter beside the belt. It puts raw food on, keeps the fire fed, and sends the food on cooked before it burns.
- **Chest portal.** A small portal on a chest, link or kitchen link. Portals with the same id share items, up to 80 m apart. Your kitchen takes its meat and wood from your chests.
- **Cookbook.** Pick up to 8 meals and how many of each to keep, for example 10 cooked boar meat. Every kitchen link on the power network cooks until you have them.
- **Narrow and short belts.** Belts 1 m wide and 0.5 m long, for a kitchen in a small house.
- **Belts are rebuilt.** A test base with 2,000 items on 1,500 belts ran at under 2 frames a second in 0.5.0. Now it runs at 17, and with two players on a server neither game slows down.
- Every player and the server need 0.6.0.

## The pieces

Build them all with the hammer, in the **Misc** tab.

| | Piece | What it does |
|:--|:--|:--|
| ![Belt](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/belt.gif) | **Belt** | Carries items and creatures. Comes 0.5 m, 1 m, 2 m and 4 m long, as a left or right corner, and as a ramp up or down, with or without pillars. |
| ![Drop floor](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/drop-floor.gif) | **Drop floor** | A floor that lets only grown creatures fall through (or only young ones). |
| ![Grinder](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/grinder.gif) | **Grinder** | Kills every creature that rides in. The loot rides on. Do not stand in it! |
| ![Item filter](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/item-filter.gif) | **Item filter** | Sends the items and creatures on its list to the side. Everything else goes straight on. Press E to pick items, families of items and creatures. You can edit the families and make your own. |
| ![Link](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/link.gif) | **Link** | Puts items into a smelter, kiln, windmill, spinning wheel or chest. It can also take items out of a chest. Press E to set its mode, how many items it moves, and a filter. |
| ![Merger](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/merger.gif) | **Merger** | Snaps across a belt. Items of one kind wait under it until the ones behind them join, so they ride on as stacks. |
| ![Kitchen link](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/kitchen-link.gif) | **Kitchen link** | A link with a greydwarf chef. Build a cooking station, iron cooking station, oven, fermenter, cauldron, mead ketill or food preparation table beside it: it snaps into place. The chef cooks the raw food that rides in on the belt and keeps the fire fed. Needs a greydwarf trophy. |
| ![Chest portal](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/chest-portal.gif) | **Chest portal** | Snaps onto a chest or a link. Portals with the same id share items, up to 80 m apart (set 5 to 80 m). On a chest it is set to Take or Give. Press E to set the id, the range, Take or Give, and a list. |
| ![Cookbook](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/cookbook.gif) | **Cookbook** | Touch it to a power network. Press E to pick the meals and a stock number for each. Every kitchen link on the network cooks them, also meals that need two stations. |
| ![Narrow pieces](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/narrow.gif) | **Narrow pieces** | Belts 1 m wide, 0.5 m, 1 m or 2 m long, a corner, a link and a kitchen link. Items over 1 m across do not fit, but a log of wood does, so a narrow kitchen link gets its wood on the belt too. |
| ![Trash box and trash bin](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/trash.gif) | **Trash box** | Snaps onto a link. Deletes what the chests and machines cannot take. |
| | **Trash bin** | Put it at the end of a belt. Items that fall in are gone. |
| ![Power mill and rope-drive post](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/power.gif) | **Power mill** | A small windmill that makes power for the other pieces. |
| | **Rope-drive post** | Carries power over a gap, with a rope to another post. |
| ![Upgrader](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/upgrader.gif) | **Upgrader** | Makes the 45 nearest pieces of its power network work faster. Level 1 (bronze) 1.5 times, level 2 (ember) 2.5 times, level 3 (blue) 4 times. |

## How a kitchen works

Belts bring the raw food and the wood. Kitchen links cook it. A cookbook on the same power network says what to cook, and how much. A kitchen link has no portal, so it takes raw food and wood only from its belt.

### Raw meat from a far chest

![Raw meat flies from a chest's portal into the portal of a chest on a link, rides past a cookbook into a kitchen link, and the cooked meat rides into the food chest](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/kitchen-portal-meat.gif)

> A chest of raw meat has a portal set to Give. A second chest sits on a link set to Out. Its portal is set to Take, with Raw meat on its list, so it pulls the meat in. The link puts the meat on the belt, the chef cooks it, and the cooked meat rides into the food chest. The cookbook's card says how many cooked meat to keep.

### Wood when the fire runs low

![The kitchen link's text says it asks for 10 wood through chest portals, the wood flies out of a portal on a link, rides into the kitchen link, and the fire lights](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/kitchen-wood.gif)

> When its fire has under 5 wood, the kitchen link asks for enough to have 10. Look at it to see how many. A link up the belt has a portal and no chest. It pulls the wood from a chest of wood whose portal is set to Give, and the wood rides down to the fire. This works only when a cookbook is on the network.

### Meals of two steps

![A kitchen link with a cauldron puts raw kale crisps on the belt, a kitchen link with an oven bakes them, and the kale crisps ride into a chest](https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/kitchen-two-steps.gif)

> Kale crisps need two stations. A cauldron at level 6 makes raw kale crisps from kale. They ride on to a kitchen link with an oven, which bakes them. One cookbook card, Kale crisps, plans both steps. If a station is missing, the card says so, for example "No stone oven on this network".

## Settings windows

Press E on a link, an item filter, a chest portal or a cookbook to open its settings. In the item filter window you can also edit a family, or make your own.

<p>
<img src="https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/link-window.png" height="320" alt="The link's settings window: the Settings tab, mode Both, a push of 10 items, a fill limit of 200 of each kind">
<img src="https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/filter-window.png" height="320" alt="The item filter's settings window: Ores, Raw meat, Boar and Leather Scraps on the list">
</p>

<p>
<img src="https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/link-filter.png" height="320" alt="The link's Filter tab: In, with Bars and Coal on the list">
<img src="https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/family-page.png" height="320" alt="The family page: Smelter stuff, a family the player made, its items each with an x, and a search to add more">
</p>

<p>
<img src="https://raw.githubusercontent.com/Preyvik/valheim-conveyor-belts-page/main/media/cookbook-window.png" height="320" alt="The cookbook window: four meals, each with its count, a bar and a stock number, and Add a meal">
</p>

## Power

Every belt, filter, grinder and link needs power from a **power mill**. Pieces that touch share the power. If there is not enough, they stop. Look at a piece to see why it stopped.

An **upgrader**, a **merger**, a **cookbook** and a **chest portal** take no power. A chest portal on a link works only while the link has power. An upgrader makes the pieces near it work faster, power mills too. One piece takes the boost of one upgrader only.

## Playing with friends

Everyone must have the mod: every player and the server.

## Install

Use a mod manager (r2modman, Gale or Thunderstore Mod Manager). It installs **BepInEx** and **Jotunn** for you.

## Settings

The costs, the power numbers, the rope length and the upgraders can be changed in the config file. Mergers can be turned off there too (`[Belts] MergeItems`), and the chest portal's top range lowered (`[Chest portal] ChestPortalMaxRange`). On a server, only an admin can change them.

Each player can also turn off `[Building] SnapToLinks`. Then chests and machines no longer snap to links. `[Building] SnapToKitchenLinks` does the same for food stations at kitchen links.

Each player can also turn on `[Pickup] AutoPickupFromBelts`. Then auto-pickup takes items off belts again.

<details>
<summary>Costs and power</summary>

| Piece | Cost | Power |
|:--|:--|:--|
| Belt 0.5 m / 1 m / 2 m / 4 m | Wood 2/3/6/12, Resin 1/1/2/4 | 0.25 / 0.5 / 1 / 2 |
| Narrow belt 0.5 m / 1 m / 2 m | Wood 2/2/4, Resin 1 | 0.25 / 0.5 / 1 |
| Narrow corner | Wood 3, Resin 1 | 1 |
| Corner, ramp | Wood 6, Resin 2 | 1 |
| Drop floor | Wood 6, Resin 2 | 1 for all tiles that touch |
| Item filter | Wood 8, Resin 2 | 2 |
| Grinder | Wood 10, Stone 10, Resin 2 | 8 |
| Link | Wood 8, Stone 12, Resin 2 | 3 |
| Narrow link | Wood 4, Stone 6, Resin 1 | 3 |
| Kitchen link | Wood 8, Stone 12, Resin 2, Greydwarf trophy 1 | 3 |
| Kitchen link (narrow) | Wood 4, Stone 6, Resin 1, Greydwarf trophy 1 | 3 |
| Chest portal | Wood 4, Greydwarf eye 2, Surtling core 1 | 0 |
| Cookbook | Stone 8, Wood 4, Leather scraps 2, Resin 1 | 0 |
| Merger | Wood 4, Resin 1 | 0 |
| Trash box | Wood 4, Resin 1 | 0 |
| Trash bin | Wood 8, Resin 2 | 0 |
| Power mill | Wood 20, Resin 2, Leather scraps 2 | gives 20 |
| Rope-drive post | Wood 8, Resin 1 | 0 (rope up to 16 m) |
| Upgrader level 1 | Wood 4, Resin 2, Bronze 1 | 0 |
| Upgrader level 2 | Wood 4, Resin 2, Iron 2, Surtling core 1 | 0 |
| Upgrader level 3 | Wood 4, Resin 2, Black metal 2, Surtling core 2, Crystal 1 | 0 |

</details>

## Made with AI

This mod was written with the help of an AI (Claude).
