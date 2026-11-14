# Changelog

## 1.0.2 — 14 November 2026

- The app now opens maximized. Un-maximize it to use it as a small window beside the game.
- Fixed the level selector, where the number was squeezed and hard to read.
- Fixed quest names showing in yellow instead of the normal text colour.

## 1.0.1 — 14 November 2026

Testing auto-update feature.

## 1.0.0 — 14 November 2026

First release of KrakowskiGuides, a leveling tracker for WoW Forever (Horde).

### The app

- **Quests:** tells you which quests to pick up next at your level, grouped by zone, for Orc, Troll, Tauren, Undead and Skyborne.
- **Route:** the full level 1–60 route with search, plus seven optional side zones including the Riverglades.
- **Talents:** an interactive talent tree and a level-by-level talent order for all 28 specs.
- **Gold:** items worth keeping, farm spots and gathering materials for your level, with a mount savings goal.
- **Desktop extras:** stays on top of the game if you want it to (switch it off in the app or the tray menu), keeps running in the system tray, and updates itself from this page.

### The KrakowskiGuides addon comes with it

The installer also puts a small WoW addon on your PC, inside the app's own folder. It is **not** copied into the game for you; you add it once:

1. In the app, open the **Desktop app** panel and click **Open addon folder**.
2. Copy the `KrakowskiGuides` folder into `World of Warcraft\_forever_\Interface\AddOns`.
3. Restart the game and make sure the addon is ticked on the AddOns screen.

What the addon does:

- It is **read-only**. It records your level, class, race, gold, quest log, completed quests, bag contents and professions so the app can follow your progress.
- It **never does anything for you** in game: no selling, buying, accepting or turning in quests, and nothing in combat.
- The game saves addon data when you log out or reload. The app picks it up automatically after that. Type `/kg` in game to see what was recorded, or `/kg save` to save right away.

With the addon in place the app sets your level, ticks off quests you have already done, marks quests that are in your quest log, and shows which valuable items are in your bags.

### Good to know

- The installer is not code-signed, so Windows SmartScreen may warn the first time. Choose "More info", then "Run anyway".
- The addon is new and has had little testing in game. If the game lists it as out of date, tick "Load out of date AddOns".
- Item and talent pictures need an internet connection.
- KrakowskiGuides is fan-made and is not affiliated with Blizzard.
