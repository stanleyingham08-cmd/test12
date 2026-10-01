# Dark Forest

A 2D top-down horror survival game in a single self-contained `index.html` (HTML, CSS and vanilla JavaScript; Canvas rendering, Web Audio sound, `localStorage` saves). Open `index.html` in a browser to play.

## The loop

Day 1 starts at 06:00 at your camp. By day you explore, gather and scavenge, then return to build, craft and upgrade. Night falls at 20:00 and lasts until 06:00. Every dawn you get a night summary, XP and a skill point. Your score is the number of nights survived.

## Features

- **Modes:** Easy, Regular and Hardcore. Hardcore has scarce supplies, smarter zombies and harsher events, saves only at dawn, and erases the run on death. Records are kept separately for each difficulty.
- **Character creation:** name, hair style and colour, skin tone, clothing and colours. Your survivor looks the same in-game.
- **Progression:** levels and XP; skill points from nights survived; a five-branch skill tree (Combat, Survival, Scavenging, Engineering, Scout) with prerequisites and capstones; perks at set levels.
- **Resources:** wood, stone, scrap, fuel, components, medical supplies, food and water. Carry limits apply; resources are stored automatically at camp. Trees, rocks and scrap piles deplete and regrow.
- **Base building:** grid placement inside the camp area.
  - Walls (wood, stone, metal), windows, doors and gates, barricades, watchtowers.
  - Traps and electric fences.
  - Workbench I–III, generator, medical station, armoury, garden, water collector, radio.
  - Lamps, searchlights and auto turrets.
  - Floors are ground: walls, doors and furniture can stand on them. Roofs rest on floors or walls.
  - Floors fully enclosed by walls/doors and covered by roofs form a house: the roof fades when you step inside, the room warms, outside sound is muffled, and zombies outside cannot see you except through windows.
  - Structures take damage, show it visually, and must be rebuilt during the day once destroyed.
- **Power:** the generator burns fuel and powers consumers up to its capacity. You choose what is powered. It is loud.
- **Weapons:** knife, hatchet, lumber axe, pistol, revolver, shotgun, SMG, hunting rifle and assault rifle, upgradeable at the workbench.
- **Zombies:** walkers, runners, crawlers, spitters, screamers, brutes, climbers, destroyers, hunters and mutants, introduced night by night.
- **Zombie AI:** zombies hear noise, notice your flashlight, chase, search your last known position, and besiege your base.
- **Night events:** Blood Moon, Blackout, The Hunter, Storm, Horde Night, Siege and Quiet Night.
- **Exploration:** 16 locations with location-specific loot, rarity tiers, keys and locked areas, and lore notes. Minimap, world map and compass.
- **Atmosphere:** a short wordless opening scene, darkness, flashlight and fog of war, positional audio, rare scripted scares, and an optional CRT prologue broadcast.
- **Endgame (optional):** repair the radio tower, transmit, and survive until rescue. You can keep playing endlessly afterwards.

## Controls

| Key | Action |
| --- | --- |
| WASD / Shift | Move / sprint |
| Mouse / Left click | Aim / shoot or swing |
| R | Reload (rotate in build mode) |
| 1–9 / Wheel | Switch weapon (category / item in build mode) |
| E (hold) | Gather, search, repair, refuel, interact |
| F / C | Flashlight on/off / shake a dead flashlight or swap battery |
| Q / G / V | Heal / throw flare / shove |
| B | Build mode (X demolish, right click exit) |
| Tab / K / M / J | Backpack / skills / map / journal (crafting and storage open at the workbench and crate) |
| Esc / P | Pause |
