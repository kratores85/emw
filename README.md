# Enderal - My Way

- [Enderal - My Way](#enderal---my-way)
- [Preamble](#preamble)
- [Installation](#installation)
    - [Pre-Installation](#pre-installation)
      - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
      - [Steam Config](#steam-config)
      - [Install Enderal](#install-enderal)
        - [Disable the Steam Overlay](#disable-the-steam-overlay)
      - [Set the Game language to English](#set-the-game-language-to-english)
      - [Clean Enderal](#clean-enderal)
      - [Start Enderal](#start-enderal)
    - [Using Wabbajack](#using-wabbajack)
      - [Preparations](#preparations)
      - [Downloading and Installing](#downloading-and-installing)
        - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
    - [Copy Game Folder Files](#copy-game-folder-files)
  - [In-Game MCM Options](#in-game-mcm-options)
  - [Tweaking Performance](#tweaking-performance)
    - [ENB: Vanilla Look ENB](#enb-vanilla-look-enb)
    - [Tweaking the ENB](#tweaking-the-enb)
    - [Tweaking the Game Settings](#tweaking-the-game-settings)
  - [Updating](#updating)
  - [Removing the Modlist](#removing-the-modlist)
- [Noteworthy Mods](#noteworthy-mods)
  - [Combat - Melee](#combat---melee)
  - [Combat - Archery](#combat---archery)
  - [Combat - Magic](#combat---magic)
  - [Quest and Encounter Mods](#quest-and-encounter-mods)
  - [Creatures](#creatures)
- [FAQ](#faq)
- [Credits and Thanks](#credits-and-thanks)
- [Contact](#contact)
- [Contributing](#contributing)
- [Changelog](#changelog)

# Preamble

![emw-banner](extra/emw.png)

Enderal - My Way is a balanced but hardcore take on the Enderal game experience with upgraded environments, improved/replaced equippable appearances and better looking NPCs.

Various bug fixes have been made and quality of life features have been included.

The combat loop has been completely overhauled by Enderal Gameplay Overhaul and Combat Gameplay Overhaul with further balancing done specifically for this list.

Crossbows have been implemented to broaden the archery options available.

# Installation

### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

#### Install Enderal

Enderal is it's own seperate entry in your Steam library.  You need to install it just like you would install Classic or Special Edition.  I recommend installing onto a SSD drive if one is available.

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

#### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Enderal

I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. You should also clean up the `Enderal` folder in `Documents/My Games/`.

#### Start Enderal

After you have done everything above and got a clean Enderal installation ready, start the Launcher and open the _Options_ menu.

1. Click on _Settings_
1. Click on _Common_
2. Set the _Aspect Ratio_ and _Resolution_ to your monitor's native values
3. Set _Antialiasing_ to _Off_
4. Select _Borderless Fullscreen_ from the dropdown

Start the game and exit once you're in the main menu.

### Using Wabbajack

#### Preparations

Let's get to the actual installation. Grab the latest release of EMW from [the release tab](https://github.com/jdsmith2816/emw/releases).

Download the release to a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in the _working folder_.

#### Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Open Wabbajack
2. Load the Modlist from Disk
3. Adjust the download and installation paths
4. Click the Go/Begin button
5. Wait for Wabbajack to finish

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you loose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait till I update the Modlist.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

## Post-Installation

### Copy Game Folder Files

Download the latest ENB Series from [here](http://enbdev.com/download_mod_tesskyrim.htm) and copy `d3d9.dll` and `enbhost.exe` from the WrapperVersion folder of the archive to your game folder.

Inside of the folder that you chose to install EMW is a folder called `Game Folder Files`.  The _contents_ of this folder must be placed into the Enderal game directory.  If you chose to install EMW to `c:/MO2 - Enderal My Way` and your steam is located at `c:/steam` then the contents of `c:/MO2 - Enderal My Way/Game Folder Files/` would need to be copied into `c:/steam/steamapps/common/Enderal/` for instance.

## In-Game MCM Options

If an MCM page or a setting on an individual page is not listed then it is either already fully pre-configured by changes I have made or it does not need adjustment from it's default state.

    Legend
    [ ] - Unchecked checkbox
    [x] - Checked checkbox
    <Selected Option> - Dropdown with the `Selected Option` option selected

- All Geared Up Derivative
  - Misc - Player
    - Scroll - Disable
    - Horn - Disable
    - Elder Scroll - Disable
    - White Phial - Disable
    - Azura's Star - Disable
  - NPC
    - Horn - Disable

- CGO
  - Settings
    - Unlocked Grip
      - Input Type <HOTKEY(TAP)>
      - Sweeping 2H Hitboxes [ ]
      - NPCs Change Grip [ ]
      - Stationary Speed Boost 0%
    - Dual Wield Blocking
      - Hotkey M3 (Whatever you prefer...)
    - Unlocked Movement
      - Power Attacks (1st Person) [ ]
      - Power Attacks (3rd Person) [ ]
      - Power Attacks (NPCs) [ ]
    - Dodge Roll
      - Input Type <HOTKEY(TAP)>
      - NPCs Dodge [ ]
    - Leaning ***(Customize as you see fit)***
      - Lean Multiplier (1st Person) x0.50
      - Lean Multiplier (3rd Person) x0.75
    - Camera Noise - ***Customize as you see fit***
      - Camera Noise Mult (1st Person) - 1.00

- Enderal Tools
  - Enderal comes with alot of crazy collectible quests... This can help you track them with quests if you want.

- Equipment HUD
  - I find this tool to be extremely valuable for playing the game without having to dive into alot of mensu.  Everything in this section is optional and should be customized to your liking.
  
  - Cyclers
    - Left-hand cycler 1 - C
    - Power/shout cycler 1 - X
    - Right-hand cycler 1 - V
    - Add to cycler - + (plus)
    - Remove from Cycler - - (minus)
    - Shift cursor left - {
    - Shift cursor right - }
- Immersive HUD
  - Activation
    - iHUD hotkey - PgDn ***(Anything that's not X if using Equipment HUD)***
- VioLens
  - Melee & Ranged
    - Melee
      - Killmoves - Off
    - Ranged
      - Killmoves - Off

## Tweaking Performance

My Setup:

- Ryzen 3700x
- 1080ti
- 32GB DDR4-3200 RAM (CL 14)
- Game and MO2 running on a Samsung 970 EVO Plus M.2 NVME SSD

### ENB: Vanilla Look ENB

[Vanilla Look ENB](https://www.nexusmods.com/enderal/mods/133) adds detailed shadows, ambient occlusion and enhanced water rendering without changing the intended look of the game. It also works with the game's Fade-to-black.

### Tweaking the ENB

This should always be the first thing you tweak. Disabling and ENB entirely can give you anything from 5 to >70 FPS depending on what you're using. The ENB this Modlist comes with (see [ENB: Vanilla Look ENB](#enb-vanilla-look-enb)) is fairly lightweight already but it can still be toned down. Open the ENB GUI using `Right Shift + Enter` (`Right Shift` is under the `Enter` key). This will open up the ENB GUI where you can enable and disable certain effects in the left panel.

- `Bloom`: Can give you up to 3 FPS, will make light sources less bright
- `DepthOfField`: Can give you up to 10 FPS, disabled by default and not really suited for gameplay
- `Ambient Occlusion`: This one is a big hitter. You can get up to 20 FPS by disabling this but the effect is very noticeable
- `Distant/DetailedShadow`: Those two can really give you a lot of FPS back depending on your shader settings (game settings). They are very noticeable.
- `ComplexFire/ParticleLights`: You won't see a lot of difference at first when disabling those two, but when particles are on screen (eg using magic or near light sources such as fires), they can _burn_ through your FPS

### Tweaking the Game Settings

I highly recommend using [BethINI](https://www.nexusmods.com/skyrimspecialedition/mods/4875) which is included in this Modlist (can be found in `MO2/tools/BethINI`). I recommend tweaking the `Detail` section for more FPS:

- `Shadow Resolution`: Very big one. A good balance is `2048` which is the borderline between high FPS drainage and garbage looking shadows.
- `Ambient Occlusion`: Highly recommended to leave this at `None`. The ENB this Modlist comes with, uses the ENB SAO which is 10x better and performance friendly than base game SAO.
- `Detailed Draw Distance`: Maybe try `2000` instead of `2800` but you won't notice a lot of FPS gain (maybe 1-3)
- `Remove Shadows`: If you really struggle, use this. This will disable all Shadows (not recommended)

## Updating

If this Modlist receives an update please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## Removing the Modlist

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

# Noteworthy Mods

[Enderal Gameplay Overhaul](https://www.nexusmods.com/enderal/mods/116) is a complete overhaul of the gameplay mechanics of Enderal. This includes a ton of balance changes, improvements to the ai, new gameplay mechanics, new weapons/spells/potions and much more.

## Combat - Melee

[Combat Gameplay Overhaul](https://www.nexusmods.com/skyrim/mods/100904) adds several features and fixes to combat and movement. It has responsive dodge rolls, procedural leaning, grip changing, mid-air combat, striking with staffs, dual-wielding two-handed weapons, 1st & 3rd person weapon animations, and more.

## Combat - Archery

[A Gentleman's Flintlock Pistol Armoury](https://www.nexusmods.com/enderal/mods/101) adds twelve different flintlock pistols to the world of Enderal. There are six models, of which two have four variations each.
The weapons are integrated into the world, so make sure to explore Pyrean ruins, and even the skeleton found the starting beach.... Most weapons have a crafting recipe as well, also found in the world.

[Enderal Crossbows](https://www.nexusmods.com/skyrim/mods/95560) adds crossbows to Enderal.

[Non-Exploitable Crossbow Reloading](https://www.nexusmods.com/skyrim/mods/94246) changes how crossbow reloading works in Enderal. No longer you will be forced to automatically reload after each shot and no longer will your crossbow reload itself when you put it away mid-reload. Now it's you who decide when it's time to pull the string.

## Combat - Magic

[ENDERAL - KataPUMB Spell Package](https://www.nexusmods.com/skyrim/mods/96908) adds forty New Spells, two new armor sets and books made like shields.

[The Forbidden Arts](https://www.nexusmods.com/enderal/mods/105) seeks to add more depth and complexity to Necromancy in Enderal. It prevents reanimated thralls from turning to ashpiles upon death, adds a new perk that extends the duration of reanimation spells, gives you the ability to interact and customize your reanimated thralls, teaches a new spell to summon them and more.

## Quest and Encounter Mods

[Disenchanted](https://www.nexusmods.com/enderal/mods/145) adds a quest in Riverville related to strange noises coming from the Old Tunnel near town.

[Fire of the Mountain](https://www.nexusmods.com/enderal/mods/125)

## Creatures

[Old Arps](https://www.nexusmods.com/enderal/mods/85) reverts the appearance of Arps to before SureAI turned them into Falmer.

[Pets of Enderal](https://www.nexusmods.com/enderal/mods/77) adds... pets... to Enderal.

# FAQ

- I'm a 21:9 resolution user and my screen looks weird
  - Search 21x9 in mod organizer and activate all of those mods.

# Credits and Thanks

- _YOU_ for actually reading the readme. Thanks a ton!!
- Lotus by erri120 - Repository template
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are they

# Contact

While I'm always available on the [Wabbajack Discord](https://discord.gg/wabbajack), I would advise checking the [Issues](https://github.com/jdsmith2816/emw/issues) (open **and** closed ones) on GitHub first if you have any problems. The same goes for _Enhancements_ or _Feature/Mod Requests_. **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS AND I WILL BLOCK YOU**.

# Contributing

See [Contributing](CONTRIBUTING.md).

# Changelog

See [Changelog](CHANGELOG.md).
