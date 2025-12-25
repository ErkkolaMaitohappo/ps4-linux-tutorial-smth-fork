# Game testing and info on how to get it running
This page is dedicated to testing and reporting ways to get games running on Linux.

> [!NOTE]
> Lots of games work but with lots of problems related to postfx (post processing effects)

> [!CAUTION]
> Some of these games have worked perfectly fine but could have been broken in the future because of Mesa. If you see such an experience, make an issue on GitHub IMMEDIATELY!

## Levels of stability and performance for PC games
There's multiple levels of stability:
- Broken
    - The game doesn't work at all
- Low
    - Major graphical glitches ruin the experience, or it just lags heavily
- Medium
    - Some issues here and there, you can still see frequent glitches
- High
    - Works for the most part, with the only issues being in specific places that don’t really affect the majority of the game
- Perfect
    - It works with no issues

> [!TIP]
> Freeing up as much RAM as possible to make some of these games launch is highly recommended. ZRAM won't help much if you have two browsers open!

## DO NOT TRY UNREAL ENGINE 5 GAMES AS THEY HAVE TOO HIGH REQUIREMENTS.

---

::: details PC Games

| Game                               | Stability | Info                                                                 | Online Support Note                              |
|------------------------------------|-----------|----------------------------------------------------------------------|--------------------------------------------------|
| Afterfall Insanity Extended Edition | Medium    | 30-60 FPS, minor stutters in heavy areas.                            | Not applicable (single-player).                 |
| Aliens vs Predator 2010            | High      | 50-60 FPS, stable.                                                   | Not applicable (single-player).                 |
| Apex Legends                       | High      | 40-50 FPS online.                                                    | No longer works on Linux due to anticheat (EA Anticheat). |
| Assetto Corsa                      | High      | 60 FPS+, stable racing.                                              | Online play possible but not tested.            |
| Battlefield 1                      | Low       | 20-40 FPS, heavy lag in multiplayer.                                 | Online play works but performance-limited.      |
| Battlefield 3                      | Medium    | 30-50 FPS, frequent glitches in maps.                                | Online play works.                              |
| Battlefield 4                      | Medium    | 30-50 FPS, drops in heavy battles.                                   | Online play works.                              |
| Battlefield 4 Premium              | Medium    | 30-50 FPS, drops in heavy battles.                                   | Online play works.                              |
| BeamNG.drive                       | Medium    | Horrible performance, tweakable for playable framerate.              | Not applicable (single-player).                 |
| Beyond Enemy Lines Remastered Edition | High      | 50-60 FPS, minor issues.                                             | Not applicable (single-player).                 |
| Black Ops 2 Plutonium              | Medium    | 40-60 FPS, stuttering in multiplayer.                                | Online play works via Plutonium.                |
| Blacksite Area 51                  | Low       | 20-40 FPS, major graphical glitches.                                 | Not applicable (single-player).                 |
| Blazblue Cross Tag Battle          | Perfect   | 60 FPS, flawless.                                                    | Online play works.                              |
| Blur                               | High      | 50-60 FPS, stable.                                                   | Not applicable (single-player).                 |
| Borderlands 2                      | High      | 40-60 FPS, minor drops.                                              | Online co-op works.                             |
| Borderlands GOTY                   | High      | 40-60 FPS, minor drops.                                              | Online co-op works.                             |
| Call of Duty 4 Modern Warfare      | High      | 60 FPS+, stable.                                                     | Online play works.                              |
| Call of Duty World at War          | Medium    | 30-50 FPS, glitches via wine.                                        | Online play not tested.                         |
| Call of Duty: Black Ops II         | Low       | 20-30 FPS, major lag and stuttering.                                 | Online play not tested (likely limited).        |
| Call of Duty: Black Ops 3          | Low       | 20-40 FPS, heavy lag.                                                | Online play performance-limited.                |
| Car Mechanic Simulator 2021        | Medium    | 30-50 FPS, stutters in menus.                                        | Not applicable (single-player).                 |
| Castlevania: Lords of Shadow       | High      | 50-60 FPS, minor issues.                                             | Not applicable (single-player).                 |
| Castlevania: Lords of Shadow 2     | High      | 50-60 FPS, minor issues.                                             | Not applicable (single-player).                 |
| Civilization V                     | Perfect   | 60 FPS, no issues (native Linux).                                    | Online play works.                              |
| Command and Conquer 3: Tiberium Wars | High      | 50-60 FPS, stable.                                                   | Online play not tested.                         |
| Command and Conquer Generals: Zero Hour | High      | 50-60 FPS, stable.                                                   | Online play not tested.                         |
| Control                            | Low       | 20-40 FPS, major glitches.                                           | Not applicable (single-player).                 |
| Counter-Strike: Global Offensive   | High      | 40-50 FPS, native online via Steam.                                  | Online play works via Steam.                    |
| Crusader Kings 2                   | Perfect   | 60 FPS, no issues.                                                   | Online play works.                              |
| Dead Cells                         | Perfect   | 60 FPS, no issues.                                                   | Not applicable (single-player).                 |
| Dead Island                        | High      | 20-60 FPS, minor stutters (native Linux).                            | Not applicable (single-player).                 |
| Dead Island Riptide                | High      | 20-60 FPS, minor stutters/shader issues.                             | Not applicable (single-player).                 |
| Dead Space                         | Medium    | 30-50 FPS, glitches.                                                 | Not applicable (single-player).                 |
| Deadpool 2013                      | High      | 50-60 FPS, stable.                                                   | Not applicable (single-player).                 |
| Detroit Become Human               | Low       | 20-40 FPS, crashes via wine.                                         | Not applicable (single-player).                 |
| Diablo III                         | Medium    | 30-50 FPS, drops during shader compiling.                            | Online play works on Linux.                     |
| Diablo IV                          | Broken    | Instant crash.                                                       | Not applicable (doesn't launch).                |
| Doom (2016)                        | Low       | 22-32 FPS, lags heavily.                                             | Not applicable (primarily single-player).       |
| Doom 3 BFG Edition                 | High      | 60 FPS, minor issues.                                                | Not applicable (single-player).                 |
| Driver San Francisco               | Medium    | 30-50 FPS, stutters.                                                 | Not applicable (single-player).                 |
| Dying Light                        | Low       | 20-40 FPS, heavy lag.                                                | Online co-op performance-limited.               |
| Elden Ring                         | Low       | 30 FPS in small window, low performance.                             | Online co-op likely works but performance-limited. |
| Enter the Gungeon                  | Perfect   | 60 FPS, no issues.                                                   | Not applicable (single-player).                 |
| F1 Race Stars                      | High      | 50-60 FPS, stable.                                                   | Not applicable (single-player).                 |
| Fallout (1997)                     | Perfect   | 60 FPS, no issues.                                                   | Not applicable (single-player).                 |
| Fallout New Vegas                  | Medium    | Playable with stuttering/freezes, 30 FPS with FSR.                   | Not applicable (single-player).                 |
| Fallout TTW                        | Medium    | Similar to Fallout New Vegas, stuttering.                            | Not applicable (single-player).                 |
| Far Cry 3                          | High      | 50-60 FPS, minor drops.                                              | Not applicable (single-player).                 |
| Fighting EX Layer                  | Perfect   | 60 FPS, flawless.                                                    | Online play works.                              |
| GRID 2                             | High      | 50-60 FPS, stable.                                                   | Online play not tested.                         |
| GTA IV                             | Broken    | Vulkan errors, unplayable, crashes (PS4 Pro).                        | Not applicable (doesn't launch).                |
| GTA Online                         | Medium    | 30-50 FPS, stutters.                                                 | Online play works but performance-limited.      |
| GTA SA                             | Broken    | Doesn't launch.                                                     | Not applicable (single-player).                 |
| GTA V                              | Low       | 20-40 FPS, heavy lag.                                                | Online play performance-limited.                |
| Garry's Mod                        | High      | 60 FPS+, stable.                                                     | Online play works via Steam.                    |
| Half-Life 2                        | Perfect   | 60-150 FPS (PS4 Pro, Nobara OS, maxed, 1080p). Minor black shader elements. | Not applicable (single-player).                 |
| Hollow Knight                      | Perfect   | 60 FPS, no issues.                                                   | Not applicable (single-player).                 |
| Jurassic Park: The Game            | Medium    | 30-50 FPS, glitches.                                                 | Not applicable (single-player).                 |
| Just Cause 2                       | High      | 60 FPS pre-OC, 75-80 post-OC in benchmark; 30-60 FPS in-game, minor lag. | Not applicable (single-player).                 |
| Kerbal Space Program               | High      | 50-60 FPS (native Linux).                                            | Not applicable (single-player).                 |
| King of Fighters XV                | Perfect   | 60 FPS online, flawless.                                             | Online play works on Linux after tweaks.        |
| Left 4 Dead 2                      | High      | 50-60 FPS, stable (native Linux).                                    | Online co-op works.                             |
| Little Nightmares                  | High      | 50-60 FPS, minor drops.                                              | Not applicable (single-player).                 |
| MOTOGP 17                          | Medium    | 30-50 FPS, stutters.                                                 | Online play not tested.                         |
| Mad Max                            | High      | 20-60 FPS, minor stutters/shader issues.                             | Not applicable (single-player).                 |
| Mafia 2                            | High      | 50-60 FPS, stable.                                                   | Not applicable (single-player).                 |
| Metal Gear Rising: Revengeance     | Perfect   | 60 FPS, no issues.                                                   | Not applicable (single-player).                 |
| Metro Last Light                   | Low       | 20-40 FPS, glitches.                                                 | Not applicable (single-player).                 |
| Midnight Driver                    | Medium    | 30-50 FPS, minor lag.                                                | Not applicable (single-player).                 |
| Minecraft 1.12 (Optifine)          | High      | 100-300 FPS vanilla, stable.                                         | Online play supported.                          |
| Minecraft 1.19.3 (Gdlauncher AppImage) | High      | 100+ FPS, stable.                                                    | Online play supported.                          |
| Mortal Kombat 9                    | Medium    | 30-60 FPS, glitches.                                                 | Online play not tested.                         |
| N64Recomp/rt64                    | High      | Audio issues on pulseaudio.                                          | Not applicable (emulation tool).                |
| Naruto Ultimate Ninja Storm 4      | Medium    | 30-50 FPS, stutters.                                                 | Online play not tested.                         |
| Need for Speed Most Wanted 2005    | High      | 50-60 FPS, stable.                                                   | Not applicable (single-player).                 |
| Need for Speed: Hot Pursuit        | High      | 50-60 FPS, stable.                                                   | Online play not tested.                         |
| Nickelodeon All-Star Brawl         | Perfect   | 60 FPS, no issues.                                                   | Online play works.                              |
| OpenRa                             | High      | 50-60 FPS, stable.                                                   | Online play works.                              |
| Orcs Must Die! 2                   | High      | 50-60 FPS, minor issues.                                             | Online co-op works.                             |
| Ori And The Blind Forest           | Perfect   | 60 FPS, no issues.                                                   | Not applicable (single-player).                 |
| Outlast                            | High      | 30-40 FPS stable (PS4 Pro, Nobara OS, medium, 1080p). Minor drops.   | Not applicable (single-player).                 |
| Overwatch 2                        | Medium    | 50 FPS with stuttering.                                              | No longer works on Linux due to anticheat (BattleEye). |
| Papers Please                      | Perfect   | 60 FPS, no issues (native Linux).                                    | Not applicable (single-player).                 |
| Path of Exile                      | Perfect   | 20-60 FPS, minor stutters/shader issues.                             | Online play works on Linux.                     |
| Planet Base                        | High      | 50-60 FPS, stable.                                                   | Not applicable (single-player).                 |
| Plants vs Zombies Garden Warfare   | Medium    | 30-50 FPS, glitches.                                                 | Online play performance-limited.                |
| Portal 2                           | Perfect   | 60-110 FPS (SteamOS3, OpenGL), no issues.                            | Online co-op works via Steam.                   |
| Puyo Puyo Tetris 2                 | Perfect   | 60 FPS, no issues.                                                   | Online play works.                              |
| Resident Evil 0 HD Remaster        | Low       | 20-40 FPS, glitches.                                                 | Not applicable (single-player).                 |
| Resident Evil 4 Remake             | Low       | 10-20 FPS, freezes on Vulkan.                                        | Not applicable (single-player).                 |
| Resident Evil 5                    | Low       | Black screen/audio issues, 20-30 FPS, crashes.                       | Not applicable (single-player).                 |
| Resident Evil 7                    | Low       | 20 FPS, heavy texture anomalies.                                     | Not applicable (single-player).                 |
| Resident Evil HD Remaster          | Low       | 20 FPS, texture issues.                                              | Not applicable (single-player).                 |
| Resident Evil Village              | Low       | Low FPS, crashes.                                                    | Not applicable (single-player).                 |
| Resident Evil: Revelations         | Low       | 20-30 FPS, crashes.                                                  | Not applicable (single-player).                 |
| Rocket League                      | High      | 50-60 FPS, stable.                                                   | Online play works.                              |
| Ruined King: A League of Legends Story | High      | 50-60 FPS, minor issues.                                             | Not applicable (single-player).                 |
| SP Football Life 2023              | Medium    | 30-50 FPS, stutters.                                                 | Online play not tested.                         |
| Saints Row: The Third              | Medium    | 30-50 FPS, frequent graphical glitches, playable.                    | Not applicable (single-player).                 |
| Scribblenauts Unlimited            | Perfect   | 60 FPS, no issues.                                                   | Not applicable (single-player).                 |
| Shadow of The Tomb Raider          | Low       | 20-40 FPS, heavy lag.                                                | Not applicable (single-player).                 |
| Silent Hill Homecoming             | Perfect   | 60 FPS, max settings, no glitches.                                   | Not applicable (single-player).                 |
| Singularity                        | Medium    | 30-50 FPS, glitches.                                                 | Not applicable (single-player).                 |
| Skyrim Together Reborn             | Medium    | 30-50 FPS, stutters in multiplayer.                                  | Online play works but performance-limited.      |
| Slime Rancher                      | Perfect   | 60 FPS, no issues.                                                   | Not applicable (single-player).                 |
| Smite                              | High      | 50-60 FPS, stable.                                                   | Online play works.                              |
| Snowrunner                         | High      | Stable, no crashes/glitches. 3GB RAM/3GB VRAM, resource-heavy.       | Online co-op works on Linux.                    |
| Sonic Adventure 2 (PC)             | High      | 50-60 FPS, minor issues.                                             | Not applicable (single-player).                 |
| Sonic And Sega All Stars Racing Transformed | High      | 50-60 FPS, stable.                                                   | Not applicable (single-player).                 |
| Sonic Roboblast 2                  | High      | 60 FPS+, stable (native).                                            | Not applicable (single-player).                 |
| Stalker: Shadow of Chernobyl       | Medium    | 30-50 FPS, glitches.                                                 | Not applicable (single-player).                 |
| Star Wars Battlefront II 2005      | Medium    | 30-50 FPS, stutters.                                                 | Online play not tested.                         |
| State of Decay 2                   | Low       | 20-40 FPS, crashes.                                                  | Online co-op performance-limited.               |
| Stray                              | High      | 50-60 FPS, minor drops.                                              | Not applicable (single-player).                 |
| Street Fighter 3rd Strike & other games offered in Fightcade | Perfect   | 60 FPS, flawless.                                                    | Online play works via Fightcade.                |
| Street Fighter 5 CE                | Perfect   | 60 FPS, no issues.                                                   | Online play works.                              |
| Street Fighter x Tekken            | Perfect   | 60 FPS, no issues.                                                   | Online play works.                              |
| Superliminal                       | Perfect   | 60 FPS, no issues.                                                   | Not applicable (single-player).                 |
| Team Fortress 2                    | High      | 50-60 FPS, stable.                                                   | Online play works via Steam.                    |
| Teardown                           | Medium    | 30-50 FPS, stutters.                                                 | Not applicable (single-player).                 |
| Technic (modded Minecraft)         | High      | 100+ FPS, stable.                                                    | Online play supported.                          |
| Teenage Mutant Ninja Turtles: 2003 | High      | 50-60 FPS, stable.                                                   | Not applicable (single-player).                 |
| Teenage Mutant Ninja Turtles: Shredder's Revenge | High      | 50-60 FPS, stable.                                                   | Online co-op works.                             |
| Teenage Mutant Ninja Turtles: in Manhattan | High      | 50-60 FPS, stable.                                                   | Not applicable (single-player).                 |
| Terrordrome: Rise of the Boogeymen | Medium    | 30-50 FPS, glitches.                                                 | Not applicable (single-player).                 |
| Test Drive Unlimited 2             | Medium    | 30-50 FPS, stutters (currently testing).                             | Online play not tested.                         |
| The Binding of Isaac               | Perfect   | 60 FPS, no issues.                                                   | Not applicable (single-player).                 |
| The Escapists 2                    | High      | 50-60 FPS, minor issues.                                             | Online co-op works.                             |
| The Forest                         | Low       | 20-40 FPS, heavy lag.                                                | Online co-op performance-limited.               |
| The Stanley Parable                | Perfect   | 60 FPS, no issues (native Linux).                                    | Not applicable (single-player).                 |
| The Walking Dead Survival Instinct | Medium    | 30-50 FPS, glitches.                                                 | Not applicable (single-player).                 |
| There's Poop In My Soup            | High      | 50-60 FPS, stable.                                                   | Not applicable (single-player).                 |
| TimeShift                          | Medium    | 30-50 FPS, glitches.                                                 | Not applicable (single-player).                 |
| Titans Quest (2006)                | High      | 50-60 FPS, stable.                                                   | Online play not tested.                         |
| Tomb Raider 2013                   | High      | 50-60 FPS, minor drops.                                              | Not applicable (single-player).                 |
| Touhou 12.3 Hisoutensoku           | Perfect   | 60 FPS, no issues (English translation).                             | Not applicable (single-player).                 |
| TrackMania Nations Forever         | High      | 60 FPS+, stable.                                                     | Online play works.                              |
| Trackmania (2020)                  | High      | 50-60 FPS, stable.                                                   | Online play works.                              |
| Tropico 3 - Steam Special Edition  | High      | 50-60 FPS, stable.                                                   | Not applicable (single-player).                 |
| Tunic                              | Perfect   | 60 FPS, no issues.                                                   | Not applicable (single-player).                 |
| Turok 2008                         | Medium    | 30-50 FPS, glitches.                                                 | Not applicable (single-player).                 |
| ULTRAKILL                          | Perfect   | 60 FPS, no issues.                                                   | Not applicable (single-player).                 |
| Ultimate Marvel vs Capcom 3        | Perfect   | 60 FPS, no issues.                                                   | Online play works.                              |
| Ultra Street Fighter 4             | Perfect   | 60 FPS, no issues.                                                   | Online play works.                              |
| Vampire Survivors                  | Perfect   | 60 FPS, no issues.                                                   | Not applicable (single-player).                 |
| Veloren                            | High      | 50-60 FPS, minor issues.                                             | Online play works.                              |
| Werewolf: The Apocalypse – Earthblood | Low       | 20-40 FPS, heavy lag.                                                | Not applicable (single-player).                 |
| WipeOut Phantom Edition            | High      | 50-60 FPS, stable.                                                   | Not applicable (single-player).                 |
| World of Warcraft                  | Medium    | 30-50 FPS, drops in heavy areas (latest release, 10.0).              | Online play works but performance-limited.      |

:::

---

::: details PC Game Fixes and Workarounds

| Game                               | Fixes and Workarounds                                                                 |
|------------------------------------|--------------------------------------------------------------------------------------|
| Alien Swarm                       | Use Proton CachyOS/Sarek with `PROTON_USE_WINED3D=1` to avoid black textures. Delete shader cache folder after failed attempts to prevent crashes. Mesa 25.1.0, Arch Linux, 2GB VRAM (PS4 fat). Reduce settings or lock to 30/45 FPS via MangoHUD for stability. |
| Apex Legends                      | Precompile shaders to reduce initial stuttering. No fix for anticheat (EA Anticheat) blocking Linux. |
| Battlefield 1                     | Lower settings to reduce lag in multiplayer. No specific fixes reported. |
| Battlefield 3                     | Adjust graphical settings to minimize glitches. No specific fixes reported. |
| Battlefield 4                     | Lower settings to reduce drops in heavy battles. No specific fixes reported. |
| Battlefield 4 Premium             | Lower settings to reduce drops in heavy battles. No specific fixes reported. |
| BeamNG.drive                      | Tweak settings heavily to achieve playable framerate. |
| Black Ops 2 Plutonium             | Lower settings to reduce stuttering in multiplayer. No specific fixes reported. |
| Blacksite Area 51                 | No specific fixes reported.                                                  |
| Call of Duty World at War         | Use wine tweaks to reduce glitches. No specific fixes reported. |
| Call of Duty: Black Ops II        | Lower settings to reduce lag and stuttering. No specific fixes reported. |
| Call of Duty: Black Ops 3         | Lower settings to improve FPS. No specific fixes reported. |
| Car Mechanic Simulator 2021       | Lower settings to reduce menu stutters. No specific fixes reported. |
| Counter-Strike: Global Offensive  | Apply performance tweaks (unspecified) for optimal FPS. Native Steam client recommended. |
| Dead Island                       | Use native Linux version to avoid glitches. No specific fixes reported. |
| Dead Space                        | Adjust graphical settings to minimize glitches. No specific fixes reported. |
| Detroit Become Human              | No specific fixes reported for wine crashes. |
| Diablo III                        | Precompile shaders to minimize FPS drops during gameplay. |
| Diablo IV                         | No specific fixes reported.                                                  |
| Doom (2016)                       | No specific fixes reported.                                                  |
| Driver San Francisco              | Lower settings to reduce stutters. No specific fixes reported. |
| Dying Light                       | No specific fixes reported.                                                  |
| Elden Ring                        | No specific fixes reported.                                                  |
| Fallout New Vegas                 | Use FSR to achieve 30 FPS. No specific fixes for stuttering/freezes. |
| Fallout TTW                       | Similar to Fallout New Vegas fixes. No specific fixes reported. |
| GTA IV                            | No specific fixes reported.                                                  |
| GTA Online                        | Lower settings to reduce stutters. No specific fixes reported. |
| GTA SA                            | No specific fixes reported.                                                  |
| GTA V                             | No specific fixes reported.                                                  |
| Half-Life 2                       | No specific fixes reported.                                                  |
| Jurassic Park: The Game           | Adjust graphical settings to minimize glitches. No specific fixes reported. |
| Just Cause 2                      | Apply overclocking to achieve 75-80 FPS in benchmark. Tweak settings to minimize in-game lag. |
| King of Fighters XV               | Set decoder to hardware to ensure flawless performance. |
| MOTOGP 17                         | Lower settings to reduce stutters. No specific fixes reported. |
| Metro Last Light                  | No specific fixes reported.                                                  |
| Midnight Driver                   | Lower settings to reduce lag. No specific fixes reported. |
| Minecraft                         | Use Mesa 25.2+ for 1.21.9+. Avoid shaders (broken). For modded versions, reduce mod count to improve FPS stability (200 mods cause 25-40 FPS). Optifine recommended for 1.12. |
| Mortal Kombat 9                   | Adjust graphical settings to minimize glitches. No specific fixes reported. |
| N64Recomp/rt64                    | Export `SDL_AUDIODRIVER=alsa` to fix audio issues on pulseaudio. |
| Naruto Ultimate Ninja Storm 4     | Lower settings to reduce stutters. No specific fixes reported. |
| Outlast                           | No specific fixes reported.                                                  |
| Overwatch 2                       | Use shader caches to reduce stuttering. No fix for anticheat (BattleEye) blocking Linux. |
| Plants vs Zombies Garden Warfare  | Adjust graphical settings to minimize glitches. No specific fixes reported. |
| Resident Evil 0 HD Remaster       | No specific fixes reported.                                                  |
| Resident Evil 4 Remake            | No specific fixes reported.                                                  |
| Resident Evil 5                   | No specific fixes reported.                                                  |
| Resident Evil 7                   | No specific fixes reported.                                                  |
| Resident Evil HD Remaster         | No specific fixes reported.                                                  |
| Resident Evil Village             | No specific fixes reported.                                                  |
| Resident Evil: Revelations        | No specific fixes reported.                                                  |
| SP Football Life 2023             | Lower settings to reduce stutters. No specific fixes reported. |
| Saints Row: The Third             | Adjust graphical settings to minimize glitches. No specific fixes reported. |
| Shadow of The Tomb Raider         | No specific fixes reported.                                                  |
| Silent Hill Homecoming            | No specific fixes reported.                                                  |
| Singularity                       | Adjust graphical settings to minimize glitches. No specific fixes reported. |
| Skyrim Together Reborn            | Lower settings to reduce multiplayer stutters. No specific fixes reported. |
| Snowrunner                        | No specific fixes reported.                                                  |
| Stalker: Shadow of Chernobyl      | Adjust graphical settings to minimize glitches. No specific fixes reported. |
| Star Wars Battlefront II 2005     | Lower settings to reduce stutters. No specific fixes reported. |
| State of Decay 2                  | No specific fixes reported.                                                  |
| Teardown                          | Lower settings to reduce stutters. No specific fixes reported. |
| Test Drive Unlimited 2            | Lower settings to reduce stutters. No specific fixes reported. |
| The Forest                        | No specific fixes reported.                                                  |
| The Walking Dead Survival Instinct | Adjust graphical settings to minimize glitches. No specific fixes reported. |
| TimeShift                         | Adjust graphical settings to minimize glitches. No specific fixes reported. |
| Werewolf: The Apocalypse – Earthblood | No specific fixes reported.                                                  |
| World of Warcraft                 | Lower settings to reduce drops in heavy areas. No specific fixes reported. |
| Afterfall Insanity Extended Edition | Lower settings to reduce stutters. No specific fixes reported. |
| Aliens vs Predator 2010           | No specific fixes reported.                                                  |
| Assetto Corsa                     | No specific fixes reported.                                                  |
| Beyond Enemy Lines Remastered Edition | No specific fixes reported.                                                  |
| Blazblue Cross Tag Battle         | No specific fixes reported.                                                  |
| Blur                              | No specific fixes reported.                                                  |
| Borderlands 2                     | No specific fixes reported.                                                  |
| Borderlands GOTY                  | No specific fixes reported.                                                  |
| Call of Duty 4 Modern Warfare     | No specific fixes reported.                                                  |
| Castlevania: Lords of Shadow      | No specific fixes reported.                                                  |
| Castlevania: Lords of Shadow 2    | No specific fixes reported.                                                  |
| Civilization V                    | No specific fixes reported.                                                  |
| Command and Conquer 3: Tiberium Wars | No specific fixes reported.                                                  |
| Command and Conquer Generals: Zero Hour | No specific fixes reported.                                                  |
| Crusader Kings 2                  | No specific fixes reported.                                                  |
| Dead Cells                        | No specific fixes reported.                                                  |
| Dead Island Riptide               | No specific fixes reported.                                                  |
| Deadpool 2013                     | No specific fixes reported.                                                  |
| Doom 3 BFG Edition                | No specific fixes reported.                                                  |
| Enter the Gungeon                 | No specific fixes reported.                                                  |
| F1 Race Stars                     | No specific fixes reported.                                                  |
| Fallout (1997)                    | No specific fixes reported.                                                  |
| Far Cry 3                         | No specific fixes reported.                                                  |
| Fighting EX Layer                 | No specific fixes reported.                                                  |
| GRID 2                            | No specific fixes reported.                                                  |
| Garry's Mod                       | No specific fixes reported.                                                  |
| Hollow Knight                     | No specific fixes reported.                                                  |
| Kerbal Space Program              | No specific fixes reported.                                                  |
| Left 4 Dead 2                     | No specific fixes reported.                                                  |
| Little Nightmares                 | No specific fixes reported.                                                  |
| Mad Max                           | No specific fixes reported.                                                  |
| Mafia 2                           | No specific fixes reported.                                                  |
| Metal Gear Rising: Revengeance    | No specific fixes reported.                                                  |
| Minecraft 1.12 (Optifine)         | Use Optifine for better performance. No specific fixes reported. |
| Minecraft 1.19.3 (Gdlauncher AppImage) | No specific fixes reported.                                                  |
| Need for Speed Most Wanted 2005   | No specific fixes reported.                                                  |
| Need for Speed: Hot Pursuit       | No specific fixes reported.                                                  |
| Nickelodeon All-Star Brawl        | No specific fixes reported.                                                  |
| OpenRa                            | No specific fixes reported.                                                  |
| Orcs Must Die! 2                  | No specific fixes reported.                                                  |
| Ori And The Blind Forest          | No specific fixes reported.                                                  |
| Papers Please                     | No specific fixes reported.                                                  |
| Path of Exile                     | No specific fixes reported.                                                  |
| Planet Base                       | No specific fixes reported.                                                  |
| Puyo Puyo Tetris 2                | No specific fixes reported.                                                  |
| Rocket League                     | No specific fixes reported.                                                  |
| Ruined King: A League of Legends Story | No specific fixes reported.                                                  |
| Scribblenauts Unlimited           | No specific fixes reported.                                                  |
| Slime Rancher                     | No specific fixes reported.                                                  |
| Smite                             | No specific fixes reported.                                                  |
| Sonic Adventure 2 (PC)            | No specific fixes reported.                                                  |
| Sonic And Sega All Stars Racing Transformed | No specific fixes reported.                                                  |
| Sonic Roboblast 2                 | No specific fixes reported.                                                  |
| Stray                             | No specific fixes reported.                                                  |
| Street Fighter 3rd Strike & other games offered in Fightcade | No specific fixes reported.                                                  |
| Street Fighter 5 CE               | No specific fixes reported.                                                  |
| Street Fighter x Tekken           | No specific fixes reported.                                                  |
| Superliminal                      | No specific fixes reported.                                                  |
| Team Fortress 2                   | No specific fixes reported.                                                  |
| Technic (modded Minecraft)        | No specific fixes reported.                                                  |
| Teenage Mutant Ninja Turtles: 2003 | No specific fixes reported.                                                  |
| Teenage Mutant Ninja Turtles: Shredder's Revenge | No specific fixes reported.                                                  |
| Teenage Mutant Ninja Turtles: in Manhattan | No specific fixes reported.                                                  |
| Terrordrome: Rise of the Boogeymen | Adjust graphical settings to minimize glitches. No specific fixes reported. |
| The Binding of Isaac              | No specific fixes reported.                                                  |
| The Escapists 2                   | No specific fixes reported.                                                  |
| The Stanley Parable               | No specific fixes reported.                                                  |
| There's Poop In My Soup           | No specific fixes reported.                                                  |
| Titans Quest (2006)               | No specific fixes reported.                                                  |
| Tomb Raider 2013                  | No specific fixes reported.                                                  |
| Touhou 12.3 Hisoutensoku          | No specific fixes reported.                                                  |
| TrackMania Nations Forever        | No specific fixes reported.                                                  |
| Trackmania (2020)                 | No specific fixes reported.                                                  |
| Tropico 3 - Steam Special Edition | No specific fixes reported.                                                  |
| Tunic                             | No specific fixes reported.                                                  |
| Turok 2008                        | Adjust graphical settings to minimize glitches. No specific fixes reported. |
| ULTRAKILL                         | No specific fixes reported.                                                  |
| Ultimate Marvel vs Capcom 3       | No specific fixes reported.                                                  |
| Ultra Street Fighter 4            | No specific fixes reported.                                                  |
| Vampire Survivors                 | No specific fixes reported.                                                  |
| Veloren                           | No specific fixes reported.                                                  |
| WipeOut Phantom Edition           | No specific fixes reported.                                                  |

:::

## Levels of stability and performance for emulation
There's multiple levels of stability:
- Broken
    - The game doesn't work at all or GPU acceleration doesn't work
- Low
    - Major graphical glitches ruin the experience, or it just lags heavily
- Medium
    - Some issues here and there, you can still see frequent glitches
- High
    - Works for the most part, with the only issues being in specific places that don’t really affect the majority of the game
- Perfect
    - It works with no issues

---

::: details Emulated Games

| Game                               | Stability | Info                                                                 | Online Support Note                              |
|------------------------------------|-----------|----------------------------------------------------------------------|--------------------------------------------------|
| Mario Kart 8 Deluxe (Yuzu)         | Low       | 20 FPS, half speed on Vulkan, unstable on OpenGL. Emulator crashes.   | Online play likely limited by performance.       |
| Zelda: Breath of the Wild (Yuzu)   | Low       | 8-14 FPS, heavy lag.                                                 | No online component.                            |
| Kirby and the Forgotten Land (Yuzu)| Low       | 20 FPS, whiteness glitch in stages.                                  | Online play likely limited.                     |
| Pokemon Brilliant Diamond (Yuzu)   | Medium    | 30 FPS, frequent issues but playable.                                | Online play possible but not detailed.          |
| Super Mario 3D World (Cemu)        | High      | 50-55 FPS with Cheat Engine speedhack, tweaks needed.                | Online co-op likely functional.                 |
| General RPCS3/3DS Emu             | Low       | 20-30 FPS max, poor performance.                                     | Online play typically unsupported.              |
| Other (e.g., Yoshi's Crafted World, Xenoblade Chronicles X) | Low/Medium | 18-25 FPS, graphical issues.                        | Online play likely limited.                     |

:::

---

::: details Emulated Game Fixes and Workarounds

| Game                               | Fixes and Workarounds                                                                 |
|------------------------------------|--------------------------------------------------------------------------------------|
| Mario Kart 8 Deluxe (Yuzu)         | Use Vulkan for slightly better performance. No specific fixes for emulator crashes. |
| Zelda: Breath of the Wild (Yuzu)   | No specific fixes reported.                                                  |
| Kirby and the Forgotten Land (Yuzu)| No specific fixes reported.                                                  |
| Pokemon Brilliant Diamond (Yuzu)   | Adjust emulator settings to reduce issues. No specific fixes reported. |
| Super Mario 3D World (Cemu)       | Use Cheat Engine speedhack and tweak Cemu settings for better FPS. |
| General RPCS3/3DS Emu             | No specific fixes reported.                                                  |
| Other (e.g., Yoshi's Crafted World, Xenoblade Chronicles X) | No specific fixes reported.                                                  |

:::