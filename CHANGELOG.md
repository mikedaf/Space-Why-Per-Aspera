# Changelog

What changed in the pack, version by version, newest first. Versions before 1.0 were played by a small group of testers.
Where it says "new land only", the change shows in areas of a world that nobody has explored yet.

## 0.9.45

- The game crashed while starting in 0.9.43 and 0.9.44: the fix that hides Embeddium's donation popup hooked the wrong part of Embeddium. Fixed.

## 0.9.44

- CurseForge removed No Chat Reports, so it is no longer part of the CurseForge pack. We strongly recommend it anyway, from Modrinth (https://modrinth.com/mod/no-chat-reports): without it, anything typed in chat can be reported to Microsoft. Put it on your server first; players can add the one jar too. With it installed, its buttons and warning screen match the pack's menus.

## 0.9.43 (new world)

- **A new world:** much of what changed only shows on new land, and the black hole moved.
- **Gargantua is twice as big,** as a supermassive black hole should be; the Future and the End moved out to match. The finale's rough edges fixed: radio lines stop once you turn back, crew stay aboard on the way in, "Welcome back" comes at the station.
- **Playing together:** ships belong to their crew and new ships start locked (`/ships lock`, `/ships unlock`). PvP works as the server sets it, but nobody can be hurt in the Trial Arena outside a versus match. One player sleeping on a long-night moon no longer skips days for everyone. Everyone who finishes gets the ending and the trophy. A ship's computer uses its own crew's star charts. Changing world no longer drags nearby ships along, arriving ships never land inside each other, and logging back in after your ship moved puts you on it.
- **Autopilot and Helios:** climbs over hills and Aether islands; STOP OUTSIDE a moon keeps pace with it; a restart mid-flight no longer drops the ship; Ctrl+T always switches engines and the void drive off; small monitors show the whole keypad.
- **Your game:** calm volume out of the box; ship alarms follow their sound sliders; the ending closes with Music at 0; shaders come back on after quitting in space; a pack update keeps your own settings; no Patreon or donate buttons anywhere in game; voice chat starts with its setup screen.
- **New land:** 4546B's ocean no longer stutters; Moon outposts and rocks sit on the ground; Europa and Callisto get ice clumps and meteor craters; Biomes O' Plenty grows on tall mountains.
- Alien villages: the shaft down to the lab stops at the ground instead of rising as a tall spire. The friendly aliens are named "Vragen (trader)" so you can see they trade.
- The pack ships its own graphics settings: Distant Horizons at 128 chunks, shaders off, Embeddium at its defaults.
- Server steadiness: two slow memory leaks fixed. Credits and third-party notices for every outside file the pack carries.

## 0.9.42 (server only)

- Pregenerating worlds overnight no longer stops part way: two memory leaks fixed, and `/spacewhy pregen` takes Chunky's words (`start`, `pause`, `continue`, `cancel`).

## 0.9.41

- **The pack's own code was read through start to finish:** flight and the autopilot, new land and saving, fixes to other mods, the story and quests, the menus and sky. Dozens of bugs fixed.
- **Autopilot:** picks a new landing spot if the old one is ruined while you come down; sees other ships on planets, in open space and in the asteroid belt and steers round them; no longer drops when you let go of the seat keys; GO TO in a planet's orbit world is much faster (200 m/s, was 60); preflight asks for a new calibration after you build onto a calibrated ship.
- **Real gravity:** ships weigh what you do on every world (light on the Moon, heavy on Tempest and Jupiter). Jupiter, Saturn, Uranus, Neptune, their small moons, the Bumblezone and the Otherside have their real gravity. Jumps on heavy worlds always clear a block (a little more hunger).
- **Venus and Mercury:** the Atlas, Helios and a chat line warn that the surface heat kills without a full Netherite Space Suit. The Warden gives 4 netherite upgrade templates, enough for the whole suit.
- **Keys:** Eureka helm C down, X cruise (like every other seat); quest book Shift+L; Epic Fight lock-on Caps Lock; AE2 wireless terminal Z; Ars spells `[` and `]`. Keys you changed yourself stay where you put them.
- New Field Manual page with every command and key, and a list of what else can kill you out there.
- Title screen: a bigger, pulsing joke line; No Chat Reports' buttons match the menus. Advancement tabs in a sensible order.
- Only your own crew can recall your ship. `/projects` is switched off for now; contracts and mail stay.
- Fixes for a rare freeze while new land is made, a rare autosave crash and a memory leak in the blueprint ghost.

## 0.9.40

- **Removed:** Fox API, CC: Eureka and Mek AE2 Infusion. A placed Infusion Converter disappears; AE2 still runs infusers with a processing pattern that exports the enriched items.
- 31 mods now use CurseForge's own copy of the same version (nothing changes in game). Old settings files of long-removed mods are cleared out.
- The rocket on the title-screen logo and the server icon flies like the one on the loading screen.
- A quieter server console. Slower PC? `/lowend on` switches to the performance setup, `/lowend off` puts everything back.

## 0.9.39

- **Versus matches in the Trial Arena:** 1 against 1 or teams, just for fun. Nobody loses items or XP; a real fight pays coins, with a cooldown.
- **The aliens and time-travel path is complete:** alien villages with traders on Earth, labs and server rooms in the Future (new land only). The Future needs a ship to reach first; after that its gate is a shortcut.
- **Flying without a ship:** jetpacks and jet suits fly all the way from Earth to open space and back. Elytra, planes and balloon ships need air: they lose lift near the top of the Aether and can't climb into orbit.
- **Deep space is cold:** far from any world your suit slowly loses heat (about 5 minutes). Near a ship you're fine.
- Fixed: a server crash from a Myrmex hive growing too far while land is made; a rare save glitch that could reset a chunk; a singleplayer freeze when tabbing out while Chunky runs; the Pioneer's Field Manual page; six item tags that didn't load. Much shorter logs.

## 0.9.38

- **Helios** is the one ship computer program, unlocked with Molly's code: autopilot, navigation, flight board, star charts, a code logbook and ship status behind one main menu that fits any computer or monitor. The ship keeps hovering while other screens are open, and the Void Engine is found by itself.
- **RCS Thruster:** a small redstone-powered nozzle for fine moves and docking. The autopilot finds it when calibrating.
- **Ship Configurator:** one tool that does every mod's wrench job and turns any block that has a direction. Old wrenches can be converted to it.
- **Clockwork:** every gas block moves gas, the Duct crash is gone, and hot air balloons fly on their own lift, up to the Aether.
- The seat-keys screen keeps your changes until you press Save, shows clashing keys in red, and has a Plane preset. Calmer crash alarms.
- Changing worlds is quicker (the land where your ship comes out is loaded first); less lag while someone flies or explores new land. Molly's compass re-aims as you travel; no outside mobs inside the Venus dome; a steadier sky.
- **Menu style** in Options: vanilla, classic or console layouts for the title, pause and options screens, and one color setting. A new Advancements window with cards. Chests, furnaces, the crafting table and the recipe book in the Space Why navy look.

## 0.9.37

- **Ships:** a new Pioneer starter ship with rear engines for flying, lift engines underneath and power from cable ducts; room to add a Void Engine and a Gravity Normalizer later.
- Ad Astra cable ducts power every block they touch (thrusters, machines, Mekanism and ZPS cables).
- Every block has a sensible ship weight; cables and ducts are light. Recalibrate the autopilot on existing ships.
- Autopilot: shuttle-shaped ships fly nose first, it asks before descending where the ship cannot hold itself up, lands more gently, steers round Apollo Station's tractor beam and looks where the ship really moves. The Ship Gauge reads a seat the way it is flown.
- New land builds much faster, also with several players exploring at once.
- Time machines spawn whole, Earth's craters are rare and only on dry land, dragon roosts are spaced out.
- Earth on the loading picture; Cold Sweat's white puffs removed; singleplayer uses less memory for far land.

## 0.9.36

- **Removed:** Immersive Engineering and PneumaticCraft (their blocks and items disappear from existing worlds). Steel comes from a Blast Furnace; plates come from the new Shipwright's Hammer.
- The Pioneer is a ship you walk into: sealed cabin, door, ladder, oxygen, lift engines and rear engines. The blueprint shows a ghost to build by; the Launch Platform and Launch Button turn it into a ship.
- Steady mode: hand-fly any ship with no calibration.
- Autopilot waypoints: save a spot, pick any world from one list, fly there or fly and land.
- Crewmates are no longer left behind; floor gravity holds on a tipped ship.
- Quests that stayed locked without a clear reason are fixed; nothing on the main route needs a world you cannot reach yet. New optional Automation chapter.
- The Trial Arena moved to Venus; the arena is unbreakable and only coins leave it. New power-climb and New Game+ loops.
- World (new land only): more bauxite and lithium, about a third more diamonds, sandy sea and river floors, three times the animals, Wanderlite ore is back, rarer dragon nests and asteroids, no more freezing seas.
- New land builds 1.5 to 2 times faster, new singleplayer worlds start on low flat ground, and land near you loads first.
- Inventory, hotbar and temperature box in the Space Why colors; a planet with a filling ring on the loading screen; the events box can be moved and resized (Ctrl+F7); the Expedition Flag is Apollo-sized.

## 0.9.35

- Field manual and quest book revised: a "From spawn to the Moon" checklist, a picture of how to wire power to thrusters, a Helios Tools page, the correct Aether height.
- The Ruined Launchpad is a proper ruin (umbilical tower, flame trench, blockhouse with a locker); it appears on dry, fairly level land.
- No Ad Astra rockets anywhere (recipes, loot, trades); you travel by ship.
- The sky-events box keeps its size at every GUI scale and never covers the minimap.
- Dread trials: a knocked-out player returns in front of the altar and is safe until the trial ends. Blasts no longer break a ship parked near the dragon fight.
- Shared comfort commands for everyone (20 homes, `/anvil`, `/hat`, `/near`); a Moderator rank; a few item-giving commands are owner-only.

## 0.9.34

- The title screen shows Saturn with its rings, Titan and the Milky Way.
- The Dread arena sits in a wide, gentle crater with terraces, a patio, an air dome and a grander coliseum: 15 rows of stands, a four-story wall and a main gate with two towers.

## 0.9.33

- The title screen reads "Space Why: Per Aspera"; advancements, pause, Cold Sweat and knocked-out screens match the Space Why look.
- The End is darker with no pink haze; airless moons have black skies; Earth's city lights show from Low Earth Orbit.
- The Dread arena has an air dome with normal gravity inside (no jetpacks or flying).
- Earth's seas are emptier on new land. The silver jetpack thruster takes Golden Amber; meteor osmium is rare.

## 0.9.32

- Fixed: with shaders on, the sky, hand and mobs could slide with the camera. Shaders start off for new players; an existing choice stays.
- Every menu and loading screen is in the Space Why look. Fixed a crash on Cancel in Multiplayer.
- The ending song starts with the poem and closes by itself.
- Helm and Maiden Voyage are one quest, The Shipwright's Helm; 17 more optional Create quests; new story lines on more worlds.

## 0.9.31

- Autopilot: finds weak gyros on heavy ships, VTOLs turn and burn properly, holds still after commands in space, keeps calibration results on screen.
- The Pioneer starter ship rebuilt as a small winged craft.
- Own title, pause and loading screens, title music, icon and logo; own ending song, shorter credits.
- Shaders and the Space Why sky work together; shaders pause in orbit and open space, and stay off if you turn them off.
- Quieter night sky, nebulas redrawn from real photos, moonlight and earthshine, Earth's city lights, a sunset for every world, Saturn's ring shadows, a redone Gargantua.
- Sky-events box with countdowns (`/events`, F7 hides it).
- Dread's Trial Arena is a coliseum; trophies can be put on display; brighter lighting on ships and in Apollo Station.

## 0.9.30

- Survival checkpoints: `/spacewhy checkpoint list` and `/spacewhy checkpoint <stage> confirm` start you at one of 12 route stages (this wipes that character first).
- Route order fixed: Mercury and Venus come before the Nether.
- Fixed overnight pregeneration pausing itself.

## 0.9.27

- Nyx, a dark rogue planet; boss lairs on Vulcan, Galia and Dune; derelict wrecks and strange signals; the Wanderer, a comet with a landable nucleus.
- Planet weather (Mars dust storms, Venus acid rain, Enceladus geysers, Io volcanoes), solar storms and auroras.
- Skill trees (Shift+P), Expedition Flags, `/log`, `/records`, a Records Board, the Helios Atlas and the real ending.
- `/contracts`, `/mail`, `/projects`, `/races`; permissions for `/crafting`, `/stonecutter`, `/smithing`, `/trashcan`, `/leaderboard` and homes; teleports only reach worlds your crew has reached by ship.
- Voyage events on long flights, loading-screen tips, `/lowend` for slower PCs. World reset.

## 0.9.26

- Orbit worlds fly at about 60 m/s; open space has a cruise lane. `/ships` lists your ships with a map waypoint; planets, moons and stars show on the FTB map.
- The first person to land on a world is announced and gets a gold trophy.
- Space music for open space, orbits and the black hole.
- Olympic Citadel chests have loot again; prizes stay with whoever earned them; smoother game on ordinary PCs.

## 0.9.25

- The Pioneer: a Ship Blueprint that builds a small, correctly wired starter ship from your own parts; five First Flight quests; a preflight check before GO (advice only).
- 4546B, a warm ocean planet near Kepler-10352.
- The Trials of Dread: an arena with 18 trials and a final boss.
- The Mi Alliance moved to the Twilight Forest. Key bindings sorted out (one-time reset of the pack's keys).

## 0.9.24

- A taller Earth with matching ores; you stand at 40 degrees north, so the seasons follow the Sun; planet years are longer to match. The Aether is the cloud layer, with living clouds.
- Walking in a moving ship works in every world; autopilot calibration progress and self-test, takeoff from a surface, obstacle look-ahead; ship air and airlocks.
- New mods: Flan's Mod, The Mi Alliance: Invasion!, Aether Villages, Chefvindicators, Hardcore Revival, FTB XMod.
- Prizes are locked to whoever earned them. World reset.

## 0.9.23

- A ship built after this version survives the Earth to Aether trip whole, with its crew.
- The Duct-Tape Suit: a cheap early suit that gives about 15 seconds of breath in a vacuum.
- Creepers heal their explosion damage (Blast Plaster). The villager chat mod was removed.

## 0.9.22

- Embeddium, Oculus and Complementary Reimagined shaders are included with fast settings; shaders pause by themselves in space.
- Seasons move at their real speed; meteor showers one night in six; animals return to tall mountains; a round telescope eyepiece.
- Much lighter on server memory.

## 0.9.21

- Drifting asteroids in the belt with ore veins, and the Tractor Beam to tow one home.
- The Ship Gauge weighs a ship and shows its center of mass and thruster balance. Re-entry heat.
- Smooth zoom (hold I) and a telescope; meteor showers and meteor impacts; planets sharpen as you descend; the Moon wears the real Moon map.
- Seasons are back on Earth. Structures never spawn inside or on top of each other. A darker Ender Dragon and a harder Wither. World reset.

## 0.9.20

- A new Earth with giant mountains, deep valleys and a cave layer. No uranium or osmium on Earth: uranium is plentiful on Mars, osmium on Mercury and Venus.
- Europa has an ocean under its ice; Dread is the dungeon planet; Jupiter has a crashed rocket.
- Autopilot: no crash at touchdown, GO TO PLANET asks whether to land, orbit or stop, RECOVER rights a crashed ship.
- Space music, hold I to zoom, season and day shown on Earth. World reset.

## 0.9.19

- Walk around inside a ship in space; a powered Gravity Normalizer in a sealed room gives that room gravity.
- Elytra and jetpacks reach the Aether and no higher.
- Every planet and moon has its own orbit world.

## 0.9.18

- A much bigger universe: planets are huge and every hop takes at least 20 minutes at 25 m/s. Other stars are far apart; the void speeds up once you leave a star's pull.
- Real day lengths for every world (the sun rises in the west on Venus and Uranus), tidally locked moons, real moon tilts.
- Eclipses (`/eclipses`), the real Milky Way and 9,000 real stars, nebulas from real photos.
- The autopilot flies like a drone: landing spots, land/orbit/stay, waypoints. A flight HUD while seated (F9 hides it).

## 0.9.17

- Autopilot saves its calibration again; new menu with a status panel and big buttons; the flight screen names each thruster's job; `go earth` works and flies round planets in the way.
- Cold is gentler, seasons last longer and announce themselves, inventory tweaks, fewer Distant Horizons pop-ups.
- Quest map tidied up; a Field Guide for Immersive Engineering (removed again in 0.9.36).
