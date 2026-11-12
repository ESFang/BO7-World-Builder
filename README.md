# BO7 World Builder

![World Builder](images/forge_tool.png)

Build your own version of any map. Place props and machines, move or delete what's already there, spawn zombies and bosses, set your own map rules, and save the whole thing so you can load it again later.

Works in Multiplayer, Zombies and Endgame on Kronos.

Current version: **v1.70.1** (scripts s1.22)

---

## Installing

### From the Workshop (easiest)

1. Open the Kronos launcher and go to the Workshop.
2. Find **BO7 - World Builder** and install it.
3. Make sure it's switched on in your mod list.
4. Close the launcher completely and open it again, then start the game.

### By hand (from a release on this page)

1. Grab the zip from the [Releases](../../releases) page.
2. Unzip it. You'll get `forge_tool` and `point_drop`.
3. Drop them into `cod25\kronos\mods\` so you end up with `cod25\kronos\mods\forge_tool\mod.json`.
4. If you had an older version, delete `cod25\kronos\mods\forge_tool\scripts\compiled`.
5. Turn them on in the launcher (or set `"forge_tool": true` in `cod25\kronos\mods.json`).
6. Restart the launcher, not just the game.

**Heads up:** the first map you load after installing or updating takes longer while the scripts get built. Load a private match on your own the first time and let it finish. After that it's fast.

If the menu footer still shows an old version number, you didn't restart the launcher.

---

## The basics

| Key | What it does |
|---|---|
| **F8** (or aim + knife) | Open / close the menu |
| **Hold F8** for 2 seconds | Put the menu back where it started |
| **Up / Down** | Move through rows |
| **Left / Right** | Change a pick (the rows with `<  >`) |
| **Enter** | Run the row |
| **Backspace** | Go back |
| **1 to 6** | Jump to a hub |
| **/** | Search every page, row and model |

New to it? Open **Saves and System > Help > Start here**. It walks you through your first object in six steps.

Nothing runs on its own. You start every mode and every change yourself.

### Editing keys

Once you've hooked something these keys do the work:

| Key | What it does |
|---|---|
| **K** | Hook whatever is in front of you |
| **Q / E** | Nudge it back / forward |
| **P** | Switch axis (X, Y, Z) |
| **U** | Switch between Move, Rotate and Scale |
| **H** | Hide / unhide it |
| **Del** twice | Delete it |
| **Z** | Undo the last change |
| **B** | Properties for a hooked machine |

Change any of them in **Settings > Key bindings**.

---

## The six hubs

Home shows six hubs. Press 1 to 6 to jump to one from anywhere.

1. **Build** - Object Library, Map Assets, Select nearby, Buyable Door
2. **Spawn** - AI, vehicles, drops and crates
3. **Player** - loadout, abilities, points and salvage, appearance
4. **World** - rounds, enemy type, map rules, zones, power, doors, sky, FX, sounds, boss fight
5. **Modes** - coming soon
6. **Saves and System** - World Saves, Settings, Help

---

## What's new in v1.70.1

### Fixes
- Menu no longer lags or fails to open big pages (Object Library, Map Assets)
- Layout Load and Start layout use a clean black fade
- Wunderfizz unlock now counts drinks from placed perk machines
- Loose change works on placed perk machines

### New
- Build > Remove & Restore: delete everything, delete what you placed, restore the map
- Power & Doors: open all, lock all, restore doors
- Mystery Box Properties: Active / Deactivated
- Portals: cost, cooldown, timed return portal and a minimap icon
- Buildable table: 3 book parts, cost to build, weapon drop with aether crystal and aether tool, table disappears or stays disabled after build
- Objectives: Press Use steps with an on-screen tracker
- Aether Crystal Properties: respawn rate and loot rarity
- Vision & Screen FX page
- Player Quotes page

---

## What's new in v1.70

### Menu
- New layout: six hubs, tabs on merged pages, search from Home, XYZ readout while editing
- Rounded menu, 14 accent themes, text color, menu size 50-120%
- UI Positioning moves the F8 menu, hint indicator, status message and hotkey bar, each with its own size and opacity. The status message shows a preview while you move it
- Help rebuilt as short topics: Start here, Menu keys, Move and edit, Place things, Saving, Fixes

### Building
- Object Library categories: Machines & assets, Buyable doors, Fast travel, Prefabs, Custom, Spawn points, Props and more
- Copied perk machines work like the map's own, one buy per press. Double Tap, Melee Macchiato and Vulture Aid copies fight zombies like the real ones
- Any perk on any map where the game can load it
- Give all perks works like Perkaholic; Eternal perks (keep when downed) is an on/off row
- Chompy (trash can) on any Zombies map
- Teleporters and portal pairs (walk-in option)
- Power switch with game-style prompt and sound; doors that open when the power comes on
- Buyable doors: copy a map door or place any model, open by price or power, custom open sound and FX
- Armor wall buys that sell your next armor level, like the map's own; placed wall buys face the right way
- Custom objectives with a tracker
- Edit menu Activate / Deactivate for Tedd, exfil, Wunderfizz, perk machines and the power switch
- Map Assets: hook any machine, trap or fast travel spot and open it in Edit
- Place an active Wunderfizz in front of you at any round
- Tedd can be activated at the nearest spot
- Delete is permanent, Hide moves things out of the way
- Delete all objects I placed (Enter twice)

### Rules and rewards
- Power: Regular, Classic (off until switched on) or Buried (switch turns it on and off)
- Wunderfizz Randomize (like the relic)
- Golden armor on/off, Aether Crystal and Aether Tool drops, rare salvage rewards
- Resources > Drop puts points on the ground for free

### Point Drop (separate mod, in the zip)
Crouch and hold **N** to drop 250 of your points for anyone to pick up.

### Removed
Gun Game, Chaos Mode, Zombie Battle, the Add-Ons page and the Tutorial page (replaced by Help). Tombstone is gone from perk lists because it isn't in BO7.

---

## Tips

- **Restart the launcher after every update.**
- Things baked into the map can't be hooked. If K grabs nothing, try **Build > Select nearby**.
- If a row stops responding, use **Settings > Fix stuck commands**.
- Saves are per map. Your layouts live in `cod25\kronos\world\`. Back that folder up if you care about your builds.

## Known issues

- Multiplayer skybox and vision changes don't work yet.
- Paradox rotates its perks, so a perk missing there isn't a bug.
- Copied perk machines work but don't play their machine animations.
- The Modes hub is marked Coming soon.

## Updating

Workshop: update it in the launcher, then restart the launcher.

By hand: replace the `forge_tool` folder and delete its `scripts\compiled` folder. Your saved layouts are in a different folder, so they stay.

---

Made by ZMRev. Questions or bugs? Open an issue on this page.
