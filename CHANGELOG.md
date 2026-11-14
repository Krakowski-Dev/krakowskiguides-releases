# Changelog

## 1.1.0 — 14 November 2026

### New: Dungeons page

- All 33 dungeons in level order, each with its level range and the level it is best run at.
- A "Run now" line shows which dungeons fit your current level, and each dungeon is marked ideal now, in range, or outleveled.
- Every dungeon lists the quests tied to it: where to pick each one up, what it asks for, and how many quests you need to finish first. Tick them off as you go.
- Bosses in order, plus where the entrance is.
- Alcaz Prison, Blackmaw Hold and Shaper's Terrace are listed but have no quest or boss details yet.

### New: Character page

- Shows what the addon recorded about your character: gear by slot (coloured by quality, hover for the item tooltip), stats, experience and rested XP, gold, skills and reputation.
- Needs the updated addon, see below.

### Addon

- **One-click install.** A new "Install addon into WoW" button copies the addon into your game folder for you.
- **Clear setup steps.** The Character page now has a five-step guide, from installing the addon to the first sync.
- **"KG Save" button in game.** A small button at the top of the screen saves your character for the app with one click (it reloads the UI, which takes a few seconds). Drag it anywhere; `/kg button` hides or shows it. It only acts when you click it and does nothing in combat.
- **The addon reads more.** It now also records gear, stats, experience, skills, reputation, guild and realm. It is still read-only and never does anything for you in game.
- **Update the addon after updating the app:** click "Install addon into WoW" again, then restart the game. The old addon keeps working for quests and bags, but the Character page stays empty until you do.

### How current is the data?

The app updates each time you click KG Save, reload the UI or log out. Addons cannot send data out of the game while you play, so it is not a second-by-second feed.

### Other

- The page tabs now wrap onto two rows in a narrow window.

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
