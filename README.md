# Space Why: Per Aspera

This is my Minecraft modpack about a physical, alternate-1970s space race. You build real ships, fly them to every planet
and moon, and follow the story of Helios from a ruined launchpad on Earth to a black hole at the edge of the map.

Travel is by ship only (Valkyrien Skies). Every planet, moon and star system can be landed on, each with its own day
length, sky, ores and weather. You can fly your ships by hand or with the autopilot, and there's a quest book, field
manuals and skill trees to guide you.

*Space Why is a fan-made pack, not affiliated with or endorsed by Mojang, Microsoft, NASA, Apple TV+ or the makers
of "For All Mankind".*

## Made with AI

I made Space Why using AI. If you want to help improve it, open an issue or a pull request.

## What you need

| | |
|---|---|
| Game | Minecraft Java Edition **1.20.1** with **Forge 47.4.x** (the launcher sets Forge up for you) |
| Java | **Java 21** recommended (what the pack is played and hosted on); Java 17 also works |
| Memory | Give the game **6-8 GB** of RAM (less than 6 GB will stutter or crash) |
| PC | A 64-bit PC with a mid-range graphics card and an SSD; the pack is large (about 1.4 GB of mods) |

**Slower PC? Type `/lowend on` in game.** One command switches the pack to its performance setup: render distance 8,
fewer entities and particles, fast graphics, no clouds, shaders off and a shorter Distant Horizons range.
`/lowend off` puts every setting back the way it was. If it's still slow, lower render and simulation distance to 6.

Good to know: Earth is very tall, and far land is built on your own computer. In singleplayer, the first minutes after
creating a world and the first visit to each planet load slowly, and joining a world takes about 40 seconds. It has not
frozen. The pack is made for Forge 1.20.1 only: other loaders, other Minecraft versions, and adding other mods to an
existing world are not supported.

## Install

Everything you need to play is on this repository's **[Releases](https://github.com/mikedaf/Space-Why-Per-Aspera/releases)**
page: open the newest release and download its files. The same pack is also on
[CurseForge](https://www.curseforge.com/minecraft/modpacks/space-why-per-aspera).

| File in each release | What it is for |
|---|---|
| `Space_Why-<version>-curseforge.zip` | The game pack. Import it in a launcher (steps below). |
| `Space_Why_Server-<version>.zip` | A server, if you want to host one for friends (see "Run a server"). |

1. In the **CurseForge app**, choose Create Custom Profile > Import and pick the `.zip`, or simply install
   Space Why from its CurseForge page. **Prism Launcher**, ATLauncher, MultiMC and GDLauncher can import the same `.zip`
   (in Prism: Add Instance > Import).
2. The launcher downloads each mod from its author's page on CurseForge; the zip itself carries Space Why's own
   files and settings, plus four mods CurseForge can't serve (listed in CREDITS.md and THIRD_PARTY_NOTICES.md). A handful of mods have their downloads switched off by their authors: a launcher other than the
   CurseForge app then asks you to download each of those by hand from the page it shows you.
3. Set the memory to 6-8 GB, start the game, and make a new world.
4. The first start can download the shader pack (needs internet). Shaders start off; turn them on in
   Options > Video Settings > Shader Packs if your PC can take it.

To update, import the newer release's `.zip` the same way (or update the pack in the CurseForge app). Your worlds stay.

Your first steps in game: open the quest book, start with *Getting Started*, and craft the Ship Blueprint for the Pioneer,
a small starter ship. The Helios Field Manual in your inventory explains the rest as you go.

**Keys you will need.** Ship, while seated: W/S forward and back, A/D turn, Space up, C down, arrows slide and tilt,
`,` and `.` roll (at a Eureka helm: C down, X cruise). Worn gear: G jetpack, H hover, Y helmet, J legs, X the ability of
what you hold. B backpack, M map, Shift+M waypoint, Z AE2 wireless terminal, Shift+L quest book, Caps Lock lock-on in
combat, P zoom, F8 flight HUD. Every key can be changed in Options > Controls.

**Spoilers.** The quest book, manual and star chart only show you what you have reached. Please keep the secret worlds
secret when you post or stream, or put a spoiler tag on them.

**Known issues.** The clock can very rarely jump by half a day (if you see it, write down what you did and report it).
The crashed rockets on Jupiter are a small pile of blocks, not a proper wreck yet. Worlds made in test versions are not supported;
start a fresh world on 1.0.

## Play with friends (multiplayer)

Everyone gets the comfort commands (homes, warps, teleport requests, a few portable crafting tables). Nobody gets cheats or
commands that skip the story. One **Moderator** rank (kick, mute, ban) is given by hand with `/ftbranks add <player> moderator`.
Operators run the admin tools (`/spacewhy ...`, `/op`, `/gamemode`). The Field Manual's *Commands and Keys* page lists
every player command.

## Run a server

1. Download the server pack (`Space_Why_Server-<version>.zip`) from the newest release on the Releases page and unpack it in an empty folder.
2. Install Java 21 and Python 3, then run the installer script from the pack (the steps are in `SERVER_SETUP.md`). It downloads the mods from their authors'
   pages and runs Forge's installer. Mods with no public link are listed in `mods_missing.txt`; add those by hand.
3. Start `run.sh` (Linux and macOS) or `run.bat` (Windows). Accept the Minecraft EULA in `eula.txt` when asked.
4. Give the server 10 GB of RAM or more (`user_jvm_args.txt`). Open port 25565 for friends outside your network.
5. The first start builds about 117 worlds and takes a long time. Then pregenerate before players join:
   `/spacewhy pregen all 1000` (one world at a time; `/spacewhy pregen status` shows progress).
6. If a trial arena is missing on an older world, an operator runs `/spacewhy trials build`.

More detail is in `SERVER_SETUP.md` inside the server pack.

## Reporting bugs

If you find a bug, please open an issue on the **Issues** page: say what happened, where you were (press F3 for your coordinates)
and the pack version (it is on the Mods list); for crashes, attach the crash report. Issues are the place for bug reports.

The in-game `/report <what happened>` command is a handy extra: it saves your note, with the time, your position and
dimension, in the `space_why_reports` folder next to the world (the game folder in singleplayer, the server folder on a
server). You can attach `reports.txt` from there to an issue.

## License

Everything I made for Space Why is under **CC BY-ND 4.0**: free to play, stream and share with credit, no modified copies
of my files. See `LICENSE`. Other mods keep their own licenses; the pack must never be sold or put behind a paywall, because
some of the mods in it are non-commercial. Every mod, author and license is listed in `CREDITS.md`.

## More

- `CREDITS.md`: mods, music, planet and sky pictures, testers.
- `CHANGELOG.md`: what changed in each version.
