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

A kitchen has three parts. **Belts** bring the raw food and the wood. **Kitchen links** cook it. A **cookbook** says what to cook, and how much.

### An example kitchen

You want 10 cooked meat in the house at all times.

1. A belt from your boar farm carries raw meat and leather.
2. The belt runs through a kitchen link with a cooking station on a campfire.
3. The belt runs on into a link set to In, with a chest on it. This is your food chest.
4. A cookbook touches one of these belts, so it is on their power network. Its card: Cooked meat, 10.

The chef takes raw meat off the belt, cooks it, and puts the cooked meat back on the belt. It rides on into the food chest. When the food chest, the belts and the kitchen link hold 10 cooked meat, the chef stops. The raw meat it does not need and the leather ride on into the food chest. Take 3 cooked meat out, and the chef cooks 3 more from the next raw meat that rides in.

### Where the raw food comes from

Only from a belt. A kitchen link takes raw food off the belt that runs into it. It takes no chest portal. So put the raw food on that belt: from a farm, or from a chest whose link is set to Out.

With a cookbook, the kitchen link takes only the raw food that its cards need. Without one, it cooks all the raw food it has room for. The rest rides on. A link set to Out empties its whole chest onto the belt, so raw food the kitchen does not take ends up at the end of the belt. To keep it out of your food chest, put an item filter before the food chest that sends Raw food to the side, into its own chest.

### Where the cooked food goes

Back onto the belt, after the kitchen link. End the belt in a link set to In, with your food chest on it.

### What the cookbook counts

The stock number counts the food on the belts of the cookbook's power network, in its kitchen links and on their stations. It also counts every chest that a link on that network fills: a belt runs into the link, and the link is set to In or Both.

It does not count a chest that a link only empties (set to Out), or a chest that only a chest portal fills. So if a portal pulls cooked food out of your food chest into another chest, the kitchen cooks more to fill the gap.

### How a chest portal takes or gives

Portals with the same id share items. A portal on a chest is set to **Take** or **Give**:

- **Take** pulls items into its chest from portals set to Give.
- **Give** lets portals set to Take pull items out of its chest.

A new portal starts on Give. Look at a portal to see which it is: its text says `Mode: Take` or `Mode: Give`. Press E to change it. The list limits it: a Take portal with Raw meat on its list pulls only raw meat. With an empty list, it takes or gives everything.

For example, your raw meat lies in 3 chests around the base. Give each of them a portal set to Give, id "meat". Put a portal set to Take, id "meat", with Raw meat on its list, on the chest at the start of the kitchen belt. That chest pulls in all the raw meat, and its link set to Out puts it on the belt.

A portal on a link has no Take or Give. It only brings wood to kitchen links, as the next part says.

### How a kitchen gets its wood

The kitchen link takes wood off its belt to feed its fire. It keeps up to 10 wood. The cooking stations, the cauldron and the mead ketill need a fire under them, and the oven burns wood too. A log rides on narrow belts as well. There are two ways to get the wood onto the belt:

1. **By hand, or from a chest.** Put wood on the belt, for example with the raw food. Wood the kitchen does not take rides on.
2. **Through a chest portal, with a cookbook.** Put a link on the belt before the kitchen link. It needs no chest. Put a chest portal on that link, with the same id as a portal set to Give on a chest of wood. When the kitchen link cooks and has fewer than 5 wood, it asks for enough to hold 10. Its text says, for example, `Asks for wood: 6 (through chest portals)`. The portal takes that much from the wood chest and puts it on the belt. No more wood moves than the kitchen asks for.

### Meals that need two stations

Some meals take two steps. For kale crisps, a cauldron at level 6 makes 4 raw kale crisps from 12 kale. Then an oven bakes them into kale crisps. The cookbook plans both steps:

1. A belt brings kale and wood into a kitchen link with a cauldron on a campfire. Build 5 cauldron upgrades near the cauldron, for level 6.
2. A belt runs on from it into a kitchen link with an oven.
3. The belt runs on into your food chest.
4. On the cookbook, add the card Kale crisps, 4.

The cauldron makes raw kale crisps only when its belt carries them to a kitchen link with an oven. The oven bakes them, and the kale crisps ride on into the food chest. You do not need a card for raw kale crisps. Add one only to keep raw kale crisps in stock too.

If a part is missing, the card says what, for example "No stone oven on this network", "Cauldron needs level 6" or "No fire under the cauldron".

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
