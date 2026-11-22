# Advanced Vice City Next Gen CE

**Play Grand Theft Auto: Vice City inside Grand Theft Auto IV.** Tommy Vercetti's story and the whole neon-lit 1986 city, rebuilt with GTA IV's lighting, physics and Euphoria animation, HD artwork, extra islands, the classic side activities and restored dialogue. It comes as one download that you copy into your own copy of **GTA IV: The Complete Edition**.

**Complete mod package** · for **GTA IV: The Complete Edition 1.2.0.59** · download **AVCNGCEFinal.zip** from [Releases](https://github.com/dillonherring9/gta-iv-modern-ryzen-apu-config/releases/latest)

- [What this is](#what-this-is)
- [What this package does](#what-this-package-does)
- [Vice City Actual Next Gen 8.0](#vice-city-actual-next-gen-80)
- [64-bit rendering, explained](#64-bit-rendering-explained)
- [What you need](#what-you-need)
- [Installation, step by step](#installation-step-by-step)
- [Controls](#controls)
- [What's in the game](#whats-in-the-game)
- [Settings](#settings)
- [Saves](#saves)
- [Troubleshooting](#troubleshooting)
- [Uninstalling](#uninstalling)
- [Source code](#source-code)
- [Credits](#credits)

> **Adult content:** this is a mature GTA game. The Pole Position club dancers, and the stripper in the club's purchase cutscene, are nude.

## What this is

**Grand Theft Auto: Vice City** is Rockstar's 2002 game. It's set in a city based on 1980s Miami, and you play Tommy Vercetti, who builds a criminal empire after a drug deal goes wrong.

**Grand Theft Auto IV** is Rockstar's 2008 game. It has a much newer engine, with realistic lighting, weighty vehicle physics and **Euphoria**, which makes characters stumble, fall and react to hits instead of playing canned animations. **The Complete Edition** (often shortened to **CE**) is the version sold today on Steam and the Rockstar Games Launcher. It includes GTA IV and its *Episodes from Liberty City*. This package targets version **1.2.0.59**.

A **total conversion** replaces a game's world and story with another one. This mod swaps GTA IV's Liberty City for Vice City and its missions, characters, vehicles, radio and sound, all running in GTA IV's engine.

**Advanced Vice City Next Gen CE** (short name **AVCNGCE**) is a complete, ready-to-play package of that conversion. It combines:

- the Vice City conversion and the large community modpack built on it, with HD vehicles, characters and textures, extra areas such as the Everglades and Gator Keys, extra vehicles and upgraded sound;
- work by other modders, such as FusionFix (fixes for GTA IV itself) and DLSS-IV (modern upscaling), all included and set up;
- this project's own work: the classic Vice City activities rebuilt as native game scripts, restored dialogue, tuned handling, native PlayStation 5 DualSense support, a wearable parachute, a separate 64-bit graphics process, and the fixes described below.

You download one archive, extract it and copy its contents into your GTA IV folder. You don't need to find, install or combine any other mod. This is an unofficial fan project. You need your own copy of GTA IV: The Complete Edition, and the base GTA IV executable and complete base game are not included.

## What this package does

- **It runs on the GTA IV you already own.** It's built for the current Complete Edition, 1.2.0.59. You don't downgrade the game, swap its executable or install Games for Windows Live.
- **Gameplay is native.** The activities, menu, weather, music and controller support are native game scripts and plugins. ScriptHook .NET and the .NET runtime aren't needed, and they aren't included.
- **Vice City's side content is in.** The rampages, hidden packages, business income, shop hold-ups, food counters, insane stunt bonuses, completion percentage and the full Vice City statistics page are native scripts.
- **The city is populated like 1986 Vice City.** Each district has the pedestrians, traffic and parked cars of the 2002 game, and the gangs hold their 2002 turf, which changes as the story moves on. Tommy can walk into Ken Rosenberg's office, and the original-style street lamps light the streets at night.
- **More of the original dialogue.** 62 original mission lines that the conversion was missing are restored across 13 missions, with subtitles in seven languages.
- **Vehicles handle like what they are.** Each car is tuned toward the real vehicle its model represents, so a Countach-style Infernus and a Humvee-style Patriot drive very differently.
- **Native DualSense support:** adaptive triggers, haptics, sound from the controller speaker and a light bar that tracks health and police. DS4Windows and Steam Input aren't needed.
- **A separate 64-bit graphics process** draws the game through DXVK and Vulkan, with automatic DLSS, FSR or XeSS. GTA IV itself stays a 32-bit program.
- **One package, set up together.** Every file is listed with a checksum. Windows, Linux and Steam Deck instructions are below.

## Vice City Actual Next Gen 8.0

Several Vice City projects for GTA IV exist, and their names are easy to mix up. This section compares **Advanced Vice City Next Gen CE** (this package) with **Vice City Actual Next Gen 8.0** by **GTATrilogyGames**. Their release is titled **Grand Theft Auto Vice City: The Actual NextGen Edition v8.0**. The page and the v8.0 post are here:

- [GTAForums thread](https://gtaforums.com/topic/1002512-grand-theft-auto-vice-city-actual-nextgen-edition/), feature list updated when v8.0 was announced
- [GitHub](https://github.com/GTATrilogyGames/ViceCityActualNextGenEditionModpack)

Both projects stand on the same foundation: Revolution Team's Vice City NextGen conversion, the VCNE and DayL community's art and restorations, and the modpack GTATrilogyGames assembled on top of that. This package also uses Kn4ckers' Complete Edition adaptation, then rebuilds the scripted features natively for patch 1.2.0.59. Selected 8.0 material is in this package, including parachute assets and the blue Soiree suit. This package is not a wrap of the whole 8.0 download, and 8.0 is not a wrap of this one.

The comparison is as fair as the public record allows. 8.0's author wrote that the v8.0 rework is too large to list from memory and has to be played to see. The rows below use that project's published feature list, plus the platform it is distributed for, set against the files and scripts in this package. A blank in their published list is not proof that a small detail is absent from 8.0. This package was not diffed file-by-file against their download.

### Where the two projects are the same

- Vice City's story, characters, radio and 1986 city, running in GTA IV's engine with Euphoria and vehicle physics.
- A large shared body of community work: HD vehicles, HD pedestrians, cutscene textures, interior overhauls, Gator Keys, the Everglades, restored weapons and map edits. The authors are named in [Credits](#credits).
- A classic-style Vice City HUD, restored side activity, upgraded sound, and a parachute Tommy can wear.
- An unofficial fan project. Neither package includes a legal copy of GTA IV.

### What this package includes that 8.0 does not publish

| Feature | Vice City Actual Next Gen 8.0 | Advanced Vice City Next Gen CE |
|---|---|---|
| Game version | Distributed for the older **1.0.8.0** game, which means a downgrade and Games for Windows Live on a Complete Edition install | **Complete Edition 1.2.0.59**. You keep the `GTAIV.exe` from that install. The mod does not replace it, and it does not ask for a downgrade |
| Script platform | .NET script mods and ScriptHook .NET | Native scripts and native plugins. No .NET runtime and no ScriptHook .NET |
| Graphics process | The 32-bit game draws its own picture. A separate 64-bit render process is not part of the published package | **VCRender** runs the drawing in a separate 64-bit process through the included DXVK and Vulkan libraries |
| Upscaling | Not in the published feature list | Automatic **DLSS** on RTX cards that can run it, **XeSS** then FSR on Intel, and **FSR** on AMD and other cards. FSR 4.1 only on cards the official AMD loader supports; every other card gets FSR 3.1. Frame generation and HDR are off |
| DualSense | Not in the published feature list | Native USB and Bluetooth: adaptive triggers, haptics, controller speaker, health and police light bar, optional gyro |
| Checksummed single package | A main download plus a separate optionals download | One archive. `SHA256SUMS.txt` names every file |
| Linux and Steam Deck instructions | Not part of the published feature list | Proton launch option, 32-bit and 64-bit support, and DualSense notes are in this guide |
| Seven text languages | Not in the published feature list | English, French, German, Italian, Spanish, Russian and Japanese, including the Japanese font |
| Windblown street litter | Not in the published feature list | The four original Vice City flying-litter images, moving with the weather wind |
| Camera droplets | Publishes restored water **and blood** drops on the screen | Water droplets stay on. The rain plugin's **screen blood is off**. Blood decals on the street and on bodies stay |
| Save-sized radio list | Their handling of the station list isn't something this guide can claim | Ten stations, including Independence FM. The station count is left alone because changing it changes the size of a save |

### What both include, and what this package does differently

| Feature | Vice City Actual Next Gen 8.0 | Advanced Vice City Next Gen CE |
|---|---|---|
| Look of the city | Published aim: PS2-like timecycle, and Ocean View Hotel lighting matched to the original Vice City. Their November 2026 rework is newer and larger than the art this package carries | Miami colour, Mint ocean water, Project Thunder storms, FusionFix, and the 64-bit host. Furnished mall interiors, mainland neon, Gator Keys night lights and a cleaner pause map from 8.0 material are included. This package does not claim a PS2-matched timecycle or a pixel match of the original Ocean View lighting |
| Wanted, death and flying music | Published as ported GTA V flying and wanted music, plus GTA IV death music | Native music plugin. Chase music starts at three wanted stars. Death music plays on death or at 10% health. Flying music is included and turned off until you enable it |
| Health recovery | Published as GTA V health regeneration | Below 25% health, three quiet seconds start a recovery of 1% per second, up to 25%. Cutscenes start and end at full health. That is a narrower rule than GTA V regeneration |
| Parachute | Part of 8.0, using The Ballad of Gay Tony assets | The same kind of Gay Tony canopy, pack, animation and sound, wired natively. Any seat of a full-size plane or helicopter gives Tommy the pack, and he can still fire guns while wearing it |
| Handling | Published as GTA V-style handling, plus fixes for odd vehicle size and animation | Each vehicle is tuned toward the real machine its model represents: weight, power, gears, drive layout, brakes and balance. Tommy is 92 kg. Vehicles are scaled to the real length of what they represent. Odd-job, mission and rampage timers are longer to suit that handling |
| Weapons and combat | Published as original Vice City behaviour and sound, tougher cops and enemies, rebalanced fist fighting, and glass that bullets pass through | Twenty guns tuned toward the real firearms they represent: damage, fire rate, magazine and range. Shotguns fire pellets. Rifles pierce armour. Thirteen weapons have their own sounds. Army and MMA melee moves are included. Glass penetration and their cop-accuracy overhaul are not features of this package |
| HUD | Published as a full interface rework toward the original, including wasted, busted and mission text | CyanFire's classic Vice City HUD, reimplemented as a native script: clock, rolling money, flashing health and armour, weapon and ammo, six stars, pink radar ring |
| Activities and statistics | Restored Vice City side content is part of the shared modpack | Rebuilt natively: 35 rampages, hidden packages, business income, pizza throws, 12 shop hold-ups, food counters, the shooting range, stunt bonuses, and completion out of 154 |
| Dialogue | Their showcases describe restored monologues, mission lines and a Lance who fights and calls for help | 62 restored lines across 13 named missions, a Cortez call after the Diaz missions, and original voices for food counters, Leaf Links, Hotring, Pole Position and the Cherry Popper purchase. This package does not include their Lance combat rewrite |
| Rain and blood on the lens | Restored water and blood drops | Fusion Rain Droplets, configured for water only |
| Tyre sound | Original Vice City tyre skid, as published | Road skid from mmtsrn1's BeamNG Sound Mod V2, adapted to the controller audio as well |
| Menu | Their own quality-of-life options and a separate optionals pack | F7 menu in pink and black. Every list is alphabetical under its commands: vehicles, weapons, teleports, clothes, objects, animations and the character list |
| Street lighting | Night-time map lighting is part of their published map work | Original-style lamps from the 2002 map, FusionFix distant lights, and the Liberty City distance cutoff turned off so Vice City's southern lamps still draw |

### What 8.0 publishes that this package does not do

These are real differences, not oversights to be papered over. 8.0's author has kept going on that 1.0.8.0 project, and the November 2026 rework is broader than the list they were willing to write down.

- **PS2-similar timecycle** and **Ocean View lighting matched to the original game**, as they describe it.
- **GTA V kill marker.**
- **GTA V-style health regeneration** as a general system. This package's recovery stops at 25% outside cutscenes.
- **Stun punch**, the unused GTA IV melee they re-enabled. This package's melee is the Army and MMA set.
- **Lose your wanted level when the police have not seen you**, and their **Pay 'n' Spray overhaul**.
- **The Hunter with all of its weapons**, as they describe that restoration.
- **Extra vehicles from San Andreas, GTA IV, GTA V and GTA Online** that they added beyond the vehicle set this package carries. This package does not claim those later additions.
- **Original Vice City tyre skid** and **original Vice City sirens on every law-enforcement vehicle**, as they describe those sounds. This package uses the BeamNG road skid and does not claim those original siren recordings.
- **Screen blood** on the camera. This package turns that off on purpose.
- **Bullets passing through glass.**
- **Grass brought toward GTA V and the Definitive Edition**, as they describe it. This package reworks beach sand and corrects mismatched ground, and it does not claim that grass replacement.
- **A separate optionals download** so players can turn large pieces on and off. This package is one configuration.
- **.NET script compatibility**, so other ScriptHook .NET mods can be dropped in. This package is native and does not load that stack.
- **Their mission reworks and Lance's combat behaviour** from the v8.0 showcases, including the Driver fail sequence, Tommy's monologues as a complete set, and the reworked Treacherous Swine and Mall Shootout. This package restores specific missing lines in Mall Shootout and twelve other missions. It does not claim those mission rewrites.
- **Blind-fire from cover**, which their public coverage has shown. It is not a feature of this package.
- **The black-and-white GTA IV death screen** they list as restored.

If a row here is wrong, the correction belongs in the credits thread with a link to the original readme. The goal of the table is to say what each project actually ships, not to declare a winner.

## 64-bit rendering, explained

**VCRender moves the graphics work into a separate 64-bit process.** GTA IV still supplies the gameplay, missions, physics and its Direct3D 9 commands. The included host renders those commands through **DXVK and Vulkan**, then displays the finished picture in the game window. You launch GTA IV normally; the host starts automatically.

The benefit is memory headroom: the graphics driver and its GPU mappings no longer take space inside the 32-bit game process. This lets the package provide a larger texture budget while keeping address-space safety limits. **GTA IV itself remains 32-bit**. This is not a replacement 64-bit `GTAIV.exe`, and it does not give the engine unlimited memory.

The renderer also includes:

- **Paired 64-bit upscaling.** The included DLSS-IV client supplies the scene, depth and motion data. Its 64-bit helper upscales before the HUD. With `upscaler=-1`, an RTX card that can run DLSS uses DLSS, Intel tries XeSS and falls back to FSR, and every other card uses FSR. FSR 4.1 is selected only when the official AMD loader supports that card. Other cards get FSR 3.1. Play on this project has used the FSR path. DLSS on an RTX card, and XeSS on Intel, are included and follow that automatic rule. They have not been confirmed here on those GPUs.
- **No frame generation and no HDR.** Leave `hdr=0`. The package does not swap in a community FSR 4 DLL.
- **GPU-side synchronization** for the upscaler, with a fallback and a watchdog if the helper stops responding.
- **One frame ahead by default,** keeping the game's rendering queue short to reduce added input delay.
- **Space for large texture dictionaries.** Blocks above 8 MiB, and blocks the original physical-resource heap cannot fit, can use a separate pool. It is capped at 512 MiB and preserves at least 600 MiB of free game address space.
- **Allocation failures and streaming diagnostics,** so the game receives real graphics errors and the logs can identify a resource that fails to load.

Frame rate depends on your CPU, GPU, resolution and graphics settings.

**Which Graphics API should I select?** Leave **Vulkan** selected and **Anti-aliasing Off**. VCRender already uses the included DXVK/Vulkan host. With the host running, that API menu setting does not switch it to a different renderer. It selects the fallback if the host cannot start. No separate DXVK installation is needed.

## What you need

- **GTA IV: The Complete Edition, version 1.2.0.59**, from Steam or the Rockstar Games Launcher. Let it update fully. To check the version on Windows, right-click `GTAIV.exe`, choose **Properties → Details** and look for **File version 1.2.0.59**.
- **Disk space:** allow about **9 GB** for the download and **9 GB** for the extracted mod. Keep about **30 GB** free while installing, in addition to the base game and your backups. Joining split parts creates another copy of the download, so allow extra space if you use that method.
- **A 64-bit operating system and a recent graphics driver compatible with DXVK 3.x.** A Vulkan 1.3-capable GPU is required, with the extensions used by the bundled DXVK. See [DXVK driver support](https://github.com/doitsujin/dxvk/wiki/Driver-support). Vulkan 1.3 support alone is not a compatibility guarantee.
- **7-Zip** to extract the download: [7-zip.org](https://www.7-zip.org/) on Windows. On Linux and Steam Deck you can use the commands in step 3 instead.
- **Windows:** install both the [Microsoft Visual C++ Redistributable **x86 and x64**](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist/). The game-side plugins need x86. The 64-bit upscaler dependencies need x64.
- **Linux and Steam Deck:** a current Proton version and graphics drivers that support the included DXVK 3.x. Proton provides compatibility for both the 32-bit game and its 64-bit host. Use a 64-bit/WoW64 prefix if you configure Wine yourself.
- **Optional:** a PlayStation 5 DualSense controller. Keyboard and mouse, Xbox and other controllers work with GTA IV's normal controls.

## Installation, step by step

### 1. Prepare GTA IV

1. Install **GTA IV: The Complete Edition** and let it finish updating.
2. Start the game once, wait for the main menu, then quit. This finishes the game's first-time setup.
3. **Start from a clean game folder.** It shouldn't contain any other mods. If you've modded GTA IV before, uninstall it, delete any leftover game folder and reinstall. Verifying the game files in Steam restores changed files but doesn't remove files that mods added.
4. **Back up your saves.** They're in `Documents\Rockstar Games\GTA IV\Profiles\`. With Proton, this folder is inside the game's Proton prefix.

### 2. Download

1. Open the [latest release](https://github.com/dillonherring9/gta-iv-modern-ryzen-apu-config/releases/latest) and scroll down to **Assets**.
2. Download **every part**, `AVCNGCEFinal.zip.001` through `AVCNGCEFinal.zip.005`, into the **same folder**. Don't rename them. Together they form one ZIP file. None of them works alone.
3. Don't download **Source code (zip)** or **Source code (tar.gz)**. GitHub adds those automatically, and they don't contain the game files. The authored source for this package is the separate `source.zip` asset, described under [Source code](#source-code).

If someone gave you the single full **AVCNGCEFinal.zip** instead, use that file and skip the parts.

### 3. Extract

**Windows:** install 7-Zip. Right-click `AVCNGCEFinal.zip.001` and choose **7-Zip → Extract files…** (on Windows 11, choose **Show more options** first). Choose a new empty folder, for example `C:\AVCNGCE`, and click **OK**. 7-Zip reads all five parts by itself. Only open `.001`. Windows' built-in ZIP tool can't open split archives.

**Linux or Steam Deck:** open a terminal in the download folder. On Steam Deck, use **Konsole** in Desktop Mode. If 7-Zip is installed:

```sh
7z x AVCNGCEFinal.zip.001 -oAVCNGCE
```

If your installed command is `7zz`, use that instead of `7z`. Without 7-Zip, join the parts into the full ZIP and extract that with an archive tool such as Ark:

```sh
cat AVCNGCEFinal.zip.00[1-5] > AVCNGCEFinal.zip
```

Either way, you get a folder named **`release`**. It contains `update`, `plugins`, `DLSSIV`, several loose files, `README.md` and `CREDITS.md`.

### 4. Find your GTA IV folder

You need the folder that contains **`GTAIV.exe`**.

- **Steam:** in your Library, right-click **Grand Theft Auto IV: The Complete Edition** and choose **Manage → Browse local files**. If you see a folder named `GTAIV`, open it.
- **Rockstar Games Launcher:** usually `C:\Program Files\Rockstar Games\Grand Theft Auto IV`.

### 5. Copy the mod in

1. Open the extracted **`release`** folder.
2. Select **everything inside it** and copy it.
3. Paste it into the folder that contains `GTAIV.exe`. Choose **Replace** (or **Overwrite**) for every file when asked.

When you're done, `GTAIV.exe`, the `update` folder and the `plugins` folder should be side by side. Don't put the `release` folder itself into the game folder.

### 6. Linux and Steam Deck only: set the launch option

In Steam, right-click the game, choose **Properties → General**, and under **Launch Options** enter:

```
WINEDLLOVERRIDES="dinput8=n,b" %command%
```

This tells Proton to load the mod's loader. In Lutris, add the DLL override `dinput8` with the value `n,b` instead.

### 7. Play

1. Start the game normally.
2. In **Settings → Display**, leave **Graphics API** on **Vulkan** and set **Anti-aliasing** to **Off**. The supplied renderer and upscaler start automatically. Use your monitor's normal resolution. The upscaler can render the scene internally at a lower resolution.
3. Choose **New Game**. A new game starts the activities, statistics and gang territories from their intended beginning. A save made with this package can be loaded too. See [Saves](#saves).

**Optional, checking the download:** `PARTS-SHA256SUMS.txt` lists the checksum of each part, and `AVCNGCEFinal.zip.sha256` lists the checksum of the full ZIP. Inside `release`, `SHA256SUMS.txt` lists every mod file. On Linux, run `sha256sum -c SHA256SUMS.txt` in that folder.

### If this folder already contains mods

A clean GTA IV CE folder is the supported starting point. Keep your saves separately, remove the old mod installation completely, and install this full package. Copying files over an unknown mod stack can leave conflicting plugins behind.

`VCCore.asi` refuses to start if `plugins/VCAudioHeap.asi`, `plugins/VCMemory.asi`, `plugins/VCMusic.asi` or `plugins/VCScriptHook.asi` is still in the folder. Remove those four if they are present. Keep this package's `ScriptHook.dll`, `VCScriptHook.ini`, `VCMusic.ini` and `VCCutscene.ini`. Use the complete VCRender folder and plugin from this package.

### DualSense setup

- Connect the controller before starting the game: by USB, or paired and connected over Bluetooth.
- **Linux and Steam Deck:** turn off Steam Input for this game in **Properties → Controller**. In Steam's Game Mode, also put `SDL_GAMECONTROLLER_IGNORE_DEVICES=` (with nothing after the `=`) in front of the launch option, so Steam doesn't hide the controller from the game:

  ```
  SDL_GAMECONTROLLER_IGNORE_DEVICES= WINEDLLOVERRIDES="dinput8=n,b" %command%
  ```

  In Lutris, add it under **System options → Environment variables** instead.
- **KDE Plasma:** if the touchpad moves the mouse while you play, disable **DualSense Wireless Controller Touchpad** in **System Settings → Touchpad**.
- **USB audio on Linux:** pick the controller's sound device, which may appear as an **Analog Surround 4.0** profile, so the speaker and haptics work.

## Controls

GTA IV's normal controls apply. The mod adds these:

| Input | Action |
|---|---|
| **F7**, or **LB + D-pad right** | Open the Vice City Menu (D-pad down also opens it) |
| Arrow keys, numpad or D-pad | Move through the menu |
| **Enter** / **A** · **Backspace** / **B** | Select · go back |
| **Ctrl+F7** | Project Thunder weather menu |
| **Alt+V** | First-person camera |
| **N** in a vehicle | Next radio track |
| **Tab** on foot | Holster your weapon |
| Get into any full-size plane or helicopter | You automatically get a parachute pack and can still use guns |
| **Sprint** while falling with the pack | Open the parachute |
| Movement controls / the air-brake buttons shown on screen | Steer / slow down while parachuting |
| **Enter Vehicle** while parachuting | Cut the parachute away |
| Aim with fists, a bat, knife, pool cue or katana, then **Z / V / C / X / G** | Army and MMA fighting moves (**F5** changes style) |

On a DualSense, Cross is A, Circle is B, Square is X and Triangle is Y.

## What's in the game

### Story, activities and progression

The full Vice City story runs in GTA IV's engine. The Everglades and Gator Keys are added alongside the original city.

- **35 rampages** at their 2002 locations. Each gives you a weapon, a briefing, a countdown and a kill counter, and vehicle rampages count vehicles destroyed.
- **Hidden packages** at their original spots, including the mall and the police station, with the classic rewards such as the chainsaw, Python, flamethrower and minigun.
- **Business income:** businesses you own earn money every day. Walk into their gold **$** pickup to collect it.
- **Pizza Boy** deliveries thrown from the scooter: the customer walks over and picks up the box, and only a pizza that reaches them counts.
- **Shop hold-ups** at 12 stores, food counters that heal you, Leaf Links golf-course security, the Downtown shooting range, insane stunt bonuses and wheelie and stoppie bonuses.
- **Completion out of 154.** Rampages, the shooting range and shop hold-ups count toward it. Robbing all 12 tracked shops shows **15** stores on the statistics page and gives the one-time completion point.
- **The Vice City statistics page:** rampages, shops, properties, assets, money collected, people saved, fires put out, pizzas delivered, hidden packages, answered phone calls and your best paramedic and firefighter levels. People saved and fires put out count each rescue and each fire, not completed levels.
- **Tutorials when you need them,** for wanted levels, hospital and police-station recovery, bribes, motorcycle balance, hotwiring and resisting disarm. The prompts show your own controls.
- **Pole Position:** varied pole and table routines, two floor dancers, and private lap dances with GTA IV animations and cameras. The rear curtain pole is empty. Buying the club, paying dancers and the club's income work as in Vice City.
- **Clubs react to violence.** Shooting or fighting in the Malibu or Pole Position stops the dancers, and the crowd flees or cowers.
- **Gang territories follow the story,** as in 2002. Diaz's men guard the mansion until **Rub Out**, then Vercetti's gang moves in, and every business you buy fills with Vercetti men. The Cuban and Haitian streets change with their war. Streetwannabes, bikers, golfers and security guards hold their 2002 areas.
- **Wanted levels work like the 2002 game.** From two stars the police keep searching, so the stars don't fade while you hide. Lose them at a Pay 'n' Spray, with a bribe, or by changing clothes outside a mission. Police don't appear on the radar. From three stars, Vice Squad Cheetahs with plain-clothes officers join the chase. Story-based limits cap the stars, and the army arrives at six.

Pickups keep Vice City's familiar shapes: the adrenaline pill, rampage skull, business money, save cassettes and green and red property icons. Health uses GTA IV's green first-aid kit.

### The city

- **Districts populated as in the 2002 game:** Cubans in Little Havana, Haitians in Little Haiti, bikers Downtown, soldiers at the army base, workers at the airport and docks, and golfers in caddies at Leaf Links. Day and night have their own mixes.
- **Classic traffic and boats,** with cheap and expensive cars in the right districts. Parked cars use the original locations and models. Added vehicles have sensible spots too: the Biplane at the airport, the Armadillo on a Downtown rooftop pad, Hotring cars by the stadium and the RC Baron beside the RC race van. Mission and reward vehicles appear where their missions put them.
- **Ken Rosenberg's office** in Washington Beach can be entered in free roam, with its corridors, stairwell and HD interior.
- **Upgraded locations:** the Vercetti mansion inside and out, Ocean View Hotel room 317, the Malibu Club, the V-Rock building, Phil's place, the junkyard, the airport access road, the Little Havana coast road, Leaf Links walls and hedges, and 1980s street details.
- **From the 8.0 modpack's material carried here:** furnished mall interiors, corrected mainland neon, night accent lights in Gator Keys and a cleaner pause-menu map.
- **Reworked beaches and ground:** dry sand with fine grain on the Atlantic beaches and Gator Keys, mapped so the main beach looks continuous from the ground and from the air. Mismatched grass, coastal paths and airport paving are corrected.
- **An airport seaplane dock** you can reach by the stairs or by boat.
- **More of the 2002 map:** palms, benches, tables, club and stadium pieces and the furniture of the lawyer's office, placed where the original game had them and solid where you'd expect.
- **Parked vehicles follow the story,** as in 2002: Diaz's boats after **Phnom Penh '86**, the mansion helicopter after **Rub Out**, the Love Fist limo after **Publicity Tour**, the Boatyard's boats once you buy it, the Sunshine Autos prize cars as you finish each import list, and the Sea Sparrow, Rhino and Hunter at 80, 90 and 100 hidden packages. The mall and Washington Beach car parks have parked cars, and a yacht lies at anchor off the Ocean Beach marina.
- **Original-style street lamps,** placed from the 2002 map, that break when hit and light the streets at night. Distant lights include those Vice City lamps. A Liberty City rule that dropped lamps beyond 300 metres is turned off, so lamps in the south of the city still draw. Palm and tree trunks are solid, while bushes, hedges and ferns can be walked through.
- **Windblown street litter.** All four original Vice City flying-litter images join suitable GTA IV paper, packets and leaves. Paper appears around roads and paving. Leaves appear near supported broadleaf trees. Movement uses the game's weather wind, and it checks for interiors, water, flight and cutscenes.

### Vehicles, physics and weapons

- **Every vehicle has its own handling,** tuned toward the real car its model represents: weight, power, acceleration, top speed, gears, drive layout, brakes, grip, ABS where fitting, and front-to-rear balance. Examples include the Infernus (Lamborghini Countach), Cheetah (Ferrari Testarossa), Turismo (Ferrari F40), Banshee (Corvette C4), Comet (Porsche 911), Sentinel (BMW 535i), Deluxo (DeLorean) and Patriot (Humvee).
- **Heavy and old vehicles feel heavy and old.** Cruisers, vans and trucks are slower and weightier than supercars.
- **Boats, helicopters, planes and RC vehicles** have their own weight and handling. The RC Bandit drives like a large RC buggy.
- **People and objects have realistic weights.** Tommy weighs 92 kg (203 lb). Street furniture, bins, bags, benches, signs, hydrants and glass have matching weights.
- **Real-size vehicles.** 118 cars, bikes, boats and aircraft are scaled to the real length of the machine they represent, with suspension and cameras to match. Boats that appear in cutscenes keep the size those scenes were made for.
- **Two more vehicles:** a second Hustler and an alternate Tropic, in traffic, in parking spots and in the F7 menu.
- **More time for odd jobs.** Paramedic, Firefighter, Vigilante, Pizza Boy, Taxi and Bloodring timers allow for the more realistic handling. Mission and rampage timers have 45 extra seconds.
- **Seaplanes work on water.** The Skimmer floats, idles and takes off from water, and the Sea Sparrow can land on it. You can't drown while seated in either.
- **The Rhino is indestructible.** Nothing damages it, its tyres can't burst and it doesn't dent. That includes the army's tanks.
- **Rhino tank shells explode.** In **Phnom Penh '86** the helicopters, and in **Supply & Demand** the boat, have double health and explode when their health runs out.
- **A wearable parachute.** Get into any full-size plane or helicopter, in any seat, and Tommy puts on a parachute pack. He can still hold and fire guns while wearing it. Jump, press **Sprint** to open the canopy, steer with the movement controls and press **Enter Vehicle** to cut away. The canopy, pack, animations, landing and sounds come from *The Ballad of Gay Tony*.
- **The 1978 Ford Fairmont police car,** restored weapons and animations, and 20 guns tuned toward the real firearms they represent: damage, fire rate, magazine size and range. Shotguns fire pellets, and rifles pierce armour.
- **Motorcycle helmets.** Tommy puts on a helmet when he gets on a motorcycle and takes it off when he gets off.
- **Euphoria for everyone,** with GTA IV's normal player ragdoll and Army and MMA melee moves. People react to gunshots and stumbles more like real people, and Tommy holds up better in long falls.
- **Injured movement.** The injured upper-body walk is a registered movement group, so those injured clips can stream.

### HUD, menu and cutscenes

- **The classic Vice City HUD,** rebuilt as a native script: clock, rolling eight-digit money, health and armour that flash when hit, weapon icon, reserve and clip ammo, six wanted stars and the pink radar ring. It adapts to your screen's aspect ratio.
- **The HUD hides when it should:** in cutscenes, fades, the Pay 'n' Spray and the wasted and busted screens, and when you turn it off in the game settings. The F7 menu adds **Hide HUD** and **No HUD in Cinematic Camera**.
- **The F7 Vice City Menu** lets you save outside missions, skip radio tracks, holster weapons and change gameplay options. In every submenu its commands come first, then the list A to Z, with Back last. The menu has a pink and black Vice City look.
- **Your outfit carries into cutscenes.** Standard outfits switch to matching high-detail Tommy models in cutscenes, including the wounded versions. That includes the blue Soiree suit. Custom outfits use the default cutscene look.
- **Health between fights:** cutscenes start and end with full health. Below 25% health, three seconds without taking damage starts a recovery of 1% per second, up to 25%. Any hit pauses it.

### Sound, music and dialogue

- **Upgraded sounds** for weapons, horns, footsteps, ambience, engines and the wasted and start tunes, and Vice City vehicle names on the police scanner. Tyre squeal on roads comes from mmtsrn1's **BeamNG Sound Mod V2**.
- **Dedicated sounds for 23 vehicles and 13 weapons** that would otherwise share generic ones, including the Fairmont police car, VCN Maverick, Rio, Coast Guard boat, Speeder, Sea Sparrow, Infernus, Pizza Boy, Tec-9, minigun, sniper rifle, M16 and AUG.
- **62 restored mission lines in 13 missions,** with subtitles in seven languages: Mall Shootout, Guardian Angels, Sir, Yes Sir!, All Hands On Deck!, Recruitment Drive, Demolition Man, Supply & Demand, Gun Runner, Cap the Collector, Keep Your Friends Close, Four Iron, Back Alley Brawl and Waste the Wife. A line waits if a conversation is already playing.
- **The Job:** the crew talks when the getaway car takes damage, and the police station warns you about carrying a weapon, with consequences if you ignore it.
- **A restored phone call from Cortez** can arrive after the Diaz missions. It's cut content from the original game, with the original recordings and translated subtitles.
- **Original activity voices:** Tommy and the food-counter staff, the Leaf Links guards, the Hotring announcer and crowd, the Pole Position dancers and the end of the Cherry Popper purchase scene.
- **Chase and death music.** Chase music starts at three wanted stars, and death music plays when you die or your health is at 10% or below. Music pauses with the pause menu. The Vice City radio stations are included, plus **Independence FM** as a tenth station.

### DualSense controller

Native PlayStation 5 DualSense support, built into the game. DS4Windows, ViGEm and Steam Input aren't needed. It works over USB and Bluetooth.

- **Adaptive triggers:** throttle and brake resistance, ABS stutter, a redline buzz, road texture and a trigger feel for each weapon.
- **Haptics** matched to Vice City's vehicle and weapon sounds: engines, firing and reloading, impacts, explosions, rough ground, gear changes and passing traffic.
- **Controller speaker:** a police siren while you're wanted, louder as police get closer. Below 20% health a heartbeat plays, faster as health falls. It also plays through your speakers and stops when you heal. Everything else plays through your PC or TV as usual. The supplied speaker volume is 100%. **Settings → Audio** can lower it in steps of 5%.
- **Light bar:** green through yellow to red as you lose health, flashing red and blue while you're wanted.
- **Player LEDs and touchpad gestures,** plus optional gyro aiming and motion steering.

### Graphics

- **HD vehicles** from Proper HD Era Vehicles, with detailed textures, badges and logos.
- **Photoreal textures:** about 5,800 Vice City textures have had a photoreal colour pass, with lettering kept sharp.
- **HD characters and world:** Tommy, cutscene characters, pedestrians in 1980s clothing, props, vegetation, roads and buildings, and improved interiors.
- **Atmosphere:** turquoise ocean and pools, Mint ocean water, a Miami sky and colour grading, Project Thunder lightning and storms, and water droplets on the camera. Getting shot does not add the rain plugin's screen blood. Blood on the ground stays.
- **Distant lights** at night: streetlights, traffic and lamp glows across Vice City, including the southern lamps. Turn them on in **Settings → Display → Distant Lights**.
- **Automatic upscaling** through the paired DLSS-IV client and 64-bit helper, alongside FusionFix's graphics fixes and options. See [64-bit rendering](#64-bit-rendering-explained).
- **Smoother running:** Mjolnir IV tunes how the game uses your CPU. Loading screens skip a redundant wait, using a fix from FusionFix's development version, adapted into `VCCore.asi`.

### Languages

Choose **English, French, German, Italian, Spanish, Russian or Japanese** in **Settings → Display → Language**. Missions, activities, statistics, graphics options and the subtitles of the restored dialogue are translated. Japanese has its own font. The pause-menu tabs stay in Latin letters because the Vice City menu font has no Japanese characters. The restored dialogue is spoken in English with translated subtitles. Vehicle, radio and brand names stay in English.

## Settings

Play the mod as supplied first. If you add other mods later, back up a working copy and add one at a time. The included features don't need ScriptHook .NET.

| File in the game folder | What you can change |
|---|---|
| `plugins/VCRender.ini` | The renderer, borderless/fullscreen handling, frame queue, extra texture budget, bounded physical-resource pool, diagnostics and whether the paired upscaler loads. |
| `DLSS-IV.cfg` | Upscaling quality, which upscaler is selected, custom render scale and sharpening. |
| `plugins/VCMusic.ini` | Chase, death and flying music, their volume and fade, the wanted level that starts the chase music, and the volume of the restored voices. |
| `plugins/GTAIV.FusionRainDroplets.cfg` | Rain droplets. `Enabled = 1` keeps water on the lens. `BloodDrops = 0` keeps screen blood off. `MaxSize = 15` is the supplied largest drop. |
| `plugins/GTA_IV_DualSense.ini` (created on first start) | Trigger and haptic strength, effects, menu light-bar colour and brightness, player LEDs, touchpad gestures, gyro aiming and motion steering. |
| `plugins/VCScriptHook.ini` | Controller speaker, Bluetooth audio, haptic strength, siren and heartbeat volume, and which effects reach the speaker. Light-bar health colours and police flashing. |
| `plugins/AudioMap.ini` | Which controller sounds and haptics each vehicle and weapon uses. |
| `plugins/VCCutscene.ini` | Whether Tommy's current outfit carries into cutscenes. |

**Upscaling:** `quality=1` is the supplied Quality preset, rendering at about two thirds of the output width and height. `custom=0` keeps that preset. `sharpness=0` adds no extra sharpening. `upscaler=-1` and `fsr_version=0` leave the choice automatic. Close the game before editing and restart afterward. To force the FSR path, set `upscaler=1`. To force FSR 3.1 even on a card that could run FSR 4, set `fsr_version=3`. NVIDIA DLSS needs an RTX card. Frame generation stays off. **HDR output is off. Leave `hdr=0`.**

**Native-resolution rendering:** in `plugins/VCRender.ini`, set `[Upscaler] Enabled=0` to keep VCRender and turn off its paired upscaler. Higher internal resolution increases GPU work. Restore `Enabled=1` to enable the upscaler again.

**Renderer queue and memory:** `MaxFramesAhead=1` is the supplied low-latency queue. Leave the texture budget and physical-pool limits at their defaults unless you are diagnosing a specific problem. Raising them cannot remove the 32-bit engine's address-space limit. Keep `plugins/global.ini`. It keeps the original root DLSS-IV plugin from loading a second time while VCRender loads its paired client.

**Turning the flying music on:** open `plugins/VCMusic.ini`. In the `[Flying]` section, change `Enabled=0` to `Enabled=1` and save.

**Your own music:** put `.mp3`, `.wav` or `.ogg` files in `plugins/VCMusic/Wanted`, `plugins/VCMusic/Death` or `plugins/VCMusic/Flying`, up to 16 per folder.

**Controller speaker categories:** in `VCScriptHook.ini`, `SpeakerEngine`, `SpeakerRoad`, `SpeakerImpacts`, `SpeakerWeapons`, `SpeakerExplosions`, `SpeakerAmbient` and `SpeakerOther` choose which effects also play from the controller speaker. At the supplied value of `0` they stay haptics only. The siren and heartbeat have their own settings. `SpeakerFilter=0` sends every effect to the speaker. `SpeakerVolume=100` is the supplied loudness.

## Saves

Save at a safehouse, or anywhere outside a mission with **F7 → Gameplay Tweaks → Save Game Now**. Saves are stored in `Documents\Rockstar Games\GTA IV\Profiles\`. With Proton, that folder is inside the game's Proton prefix. Gang territories are stored in the save, so start a **New Game** to get them. An older save keeps the territories it was made with. Parked vehicles follow the installed files and work with any save made with this package.

The radio-station list has ten stations, including Independence FM. That count is part of the save size, so this package leaves it alone. A save made with this package keeps that layout. Saves from a different Vice City conversion, or from unmodded GTA IV, are not interchangeable with this package.

Back up `Profiles` before you install, and keep the backup outside the game folder.

## Troubleshooting

- **7-Zip says a volume is missing or the archive is corrupt.** Confirm that `AVCNGCEFinal.zip.001` through `.005` are together, with their exact original names. Check `PARTS-SHA256SUMS.txt` and download a failing part again. Extract only from `.001`.
- **The game starts as normal GTA IV in Liberty City.** Check that `GTAIV.exe`, `dinput8.dll`, `update` and `plugins` are together. On Proton, use the launch option in step 6. Do not leave the files inside an extra `release` folder.
- **Only a tiny IV icon appears during startup.** Use the complete matching renderer pair, save the logs, and note whether the same installation gets past that point in Desktop Mode or Lutris.
- **The game closes or cannot start.** Start with a clean CE 1.2.0.59 installation, the complete matching package and current GPU drivers. On Windows, install both the x86 and x64 Visual C++ Redistributables. Remove the four old standalone plugins named in the install section if they are present. `plugins/GTAIV.XboxRainDroplets.asi` must not be installed beside Fusion Rain Droplets. The Fusion rain plugin closes the game if the older rain plugin is still there. A 32-bit operating system cannot run the host.
- **No upscaling, or an unexpectedly soft picture.** Keep Anti-aliasing Off, restart after changing settings, and check `DLSS-IV.cfg`. Automatic mode picks DLSS, XeSS or FSR from the card. For FSR on any card, set `upscaler=1`. Do not install a second DLSS-IV, and do not replace the paired files or the FSR DLLs.
- **I changed DirectX/Vulkan and the picture stayed the same.** That is expected while VCRender's host is running. Leave Vulkan selected. The menu setting controls the fallback rather than the active host.
- **Loading artwork disappears at a particular resolution.** Apply or reset the display setting and try another supported resolution, or your monitor's native resolution.
- **Missing roads or buildings after prolonged travel.** Keep the renderer's default memory limits, copy the logs before restarting, and report the location and route.
- **The DualSense is not detected.** Connect it before starting. On Linux and Steam Deck, turn off Steam Input and add `SDL_GAMECONTROLLER_IGNORE_DEVICES=` as described in [DualSense setup](#dualsense-setup).
- **Reporting a problem:** open a [GitHub issue](https://github.com/dillonherring9/gta-iv-modern-ryzen-apu-config/issues) with your OS, GPU and driver, resolution, mission or location, and what you did before the problem. Copy logs before relaunching: `plugins/VCRender.log`, `plugins/VCRender/logs/`, `plugins/VCRender/VCBridge-upscale-helper.log`, `DLSS-IV.log` and the relevant plugin logs. A new launch can replace them.

## Uninstalling

The simplest way is to uninstall GTA IV, delete what's left of its folder and reinstall it. To remove only the mod, delete every file listed in `SHA256SUMS.txt` from the game folder, then use **Verify integrity of game files** in Steam (or the Rockstar Games Launcher equivalent) to restore the original game files the mod replaced. Keep your `Profiles` saves folder. It isn't part of the mod.

## Source code

The authored source for this package is `source.zip`, attached beside the game parts. Extract it and read `Source/README.md` and `Source/BUILDING.md`. The game scripts, native plugins and renderer sources are under `Source/`. Textures, models and sound are in the five `AVCNGCEFinal.zip` parts, with their creator credits.

GitHub's automatic **Source code (zip)** and **Source code (tar.gz)** buttons download the repository, not this package and not `source.zip`.

## About this project

Advanced Vice City Next Gen CE is an unofficial fan project. It isn't affiliated with or endorsed by Rockstar Games, Take-Two Interactive, Sony Interactive Entertainment, Intel, AMD or NVIDIA. You need your own copy of GTA IV: The Complete Edition. Please support the original creators listed below.

## Credits

The full credit list is in [CREDITS.md](CREDITS.md), included beside this file. Rockstar made the original games. Revolution Team, Kn4ckers, GTATrilogyGames and the VCNE and DayL communities made the Vice City conversion and the modpack this package builds on. ThirteenAG, ChunkLeChuck, the DXVK authors, AMD, NVIDIA, Intel, NodixTech, ItsClonkAndre, MrOort and the other people named in that file made the tools and art this package includes.
