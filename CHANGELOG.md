# Changelog

## 1.3.0 — 15 November 2026

- **New look.** Softer and calmer: rounded panels separated by tone instead of heavy outlines, no more hard shadows or slanted labels, and sentence-case headings in place of the all-caps block letters.
- **Navigation on the side.** In a wide window the pages and your character (level, race, class, spec, progress) sit in a column on the left and stay put while you scroll. In a small window beside the game they fold into a top bar with scrolling tabs.
- **Settings page.** Backups, always on top, the addon file and updates moved to their own page. The Quests page keeps a slim line with the addon status, "Install addon into WoW" and "Sync from addon".
- **Bag glow for items worth auctioning.** In game, bag items that sell for more at the auction house than at a vendor now glow teal, a different colour from the yellow quest-item glow. It uses the prices from KG Scan or your own searches, so it shows nothing until the addon has seen prices. `/kg glow` switches it off or on. It works on the game's own bags, not on bag addons.
- **Only gear and crafting materials count.** The glow and the Gold page's "auction or vendor" list now skip grey items, food and drink (including conjured mage food), potions, quest items and anything soulbound.
- **Update the addon for these two:** click "Install addon into WoW" again and restart the game.
- **Smoother.** Pages cross-fade when you switch, lists ease open, and progress bars glide.

## 1.2.0 — 14 November 2026

- **Upgrades from dungeons.** The Character page now lists dungeon boss drops with a higher item level than what you are wearing, slot by slot, with the dungeon and boss that drops each one. It only shows items your class can use and that you can equip within two levels. Covers 274 drops from 16 dungeons, up to the mid-40s.
- **Dungeon quest rewards count as upgrades too.** The same list now also suggests gear you get from dungeon quests, marked "Quest:" with the quest name and "pick one" where the quest lets you choose. Covers 84 rewards from 37 Horde quests in 15 dungeons. The Dungeons page lists the same rewards under each quest; ones your class cannot use are dimmed.
- **Auction house prices.** The addon now records the lowest buyout it sees while you have the auction house open, from your own searches or from the new **KG Scan** button next to KG Save. It only reads prices; it never bids, buys or posts. After KG Save, the Gold page lists your sellable bag items with "auction", "vendor" or "keep", the price each and the total, and shows whether a price rose or fell since the last day you scanned. Prices are your realm's, as fresh as your last visit. New and untested in game: if KG Scan reports that the game refused the scan, your own searches are still recorded.
- **Update the addon for this:** the addon now also records item levels. Click "Install addon into WoW" again, restart the game and press KG Save. Until then only empty gear slots get suggestions.
- **The window remembers itself.** The app reopens at the size and position you left it, maximized or not. The first launch is still maximized.
- **Quests are matched by their game ID.** The addon now also sends the ID of every quest you completed or have in your log, and the app ticks exactly that quest. Before, two quests with the same name in different zones were both ticked. If your last addon save is from an older version, the app still matches by name until you save again. Click "Install addon into WoW" again, restart the game and press KG Save to get this.
- **Full quest chains.** For 63 of the 198 quest chains the list now shows every quest of the chain in order: click "chain: 0/3 done" under a quest. Tick the steps one by one, or tick the quest to tick them all; the quest counts as done when all its steps are. The addon ticks steps by itself. The other chains still show "+N follow-ups" and you tick the quest yourself when the chain is done, because no step list that agreed with the route data was available for them.
- **"Do next" is now a walking route.** Inside each zone the quests are grouped by quest hub (givers standing close together), each hub is named after its main quest giver with coordinates, and the hubs are ordered so you walk from one to the nearest next one. Where the quest is handed in somewhere else, the row says "turn in at" with the place and coordinates (about 40% of the quests have that; the rest are handed in to the giver or the place is unknown).
- **Trainer reminder.** At every even level "Do next" reminds you to visit your class trainer.

## 1.1.1 — 14 November 2026

- The "Install addon into WoW" button is now also on the front page, in the Desktop app panel, so you don't have to go to the Character page to find it.

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
