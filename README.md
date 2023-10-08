# Mei Configs
### `Discord` MeiRiver

***I have no responsibility for what may happen to your account if you use these Configs. Keep in mind these files are against the APB EULA however they are approved by Little Orbit!***

**Feel free to add or remove any feature you like ^.^**

# Graphics
### Five graphic presets, choose one in the game options!
***Note:*** **If you change preset while in game you must change district to make the changes effective. In some cases the game may crash!**
- `Performance` The default preset. High FPS and low textures, useful for slower computers.
- `Low Shadows` Performance preset with low quality shadows.
- `Balanced` My personal choice! A good balance between performance and quality, useful for decent computers.
- `High Shadows` Balanced preset with high quality shadows.
- `Quality` Not recommended. Low FPS but incredible quality, useful for customizing cars, characters and clothes.

# Keybinds
### I have completely redone, sorted and optimized the structure of the keybinds, with many new ones too! You can customize any key from the game options.
***I recommend resetting all in-game keybinds to default after installing this configuration.***
- `Sprint (Inverted-Jog)` Reverse the Sprint key to make you Sprint endlessly, hold it down to Jog. When you join a district press the key once to start Sprinting.
- `Sprint (Inverted-Walk)` Reverse the Sprint key to make you Sprint endlessly, hold it down to Walk. When you join a district press the key once to start Sprinting.
- `Crouch (Hold)` Hold down the key to Crouch, release it to stand up. If you press Crouch and Jump at the same time you will get stuck in the Crouch position, press Jump again to stand up.
- `Grenade (Toggle)` Press the Grenade key once to start cooking it then press the Fire key to throw! I suggest using it for Grenades only, while for Half-Bricks and Eight-Balls use the ***Grenade (Hold)*** key.
- `Lean (Hold)` Hold down the key while aiming. It's difficult to move around.
- `Scoreboard (Hold)` Hold to display the Scoreboard. Can be used to quickly close the inventory menu while changing weapons.
- `Map (Hold)` Hold to show the Map. Similar use to Scoreboard.
- `Abandon Mission` Use to quickly abandon the mission.
- `Music Player` Right-Shift to Open the Music Player, Right-CTRL to Play/Pause, Arrow keys to change Tracks and adjust the Volume.
- `Social` Open customization kiosks in Social. They are Character Customisation, Clothing Customisation, Vehicle Customisation, Symbol Editor, Music Studio.
- `Alt+F4` Ragequit **:p**

# Settings
- `Advanced APB Launcher` ***NOT*** compatible with these configs!
- `Language` You need to set the game language to `-language=1031` for the Localization. Don't worry, the game will stay in English.
- `Resolution` Ultra-Low resolutions are now available in the game options. Default one is `1920x1080`.
- `Double Buffering` Depending on your hardware you may want to enable it in the game options, it will give you a significant FPS boost but it will also increase input latency.
- `Bloom` To keep the transparent background without the Bloom go to `Engine\Config` open `BaseEngine.ini` with Notepad and put `;` before `DefaultPostProcessName=APBPostEffectMaterials.APBPostEffect_Process`.
- `Muzzle Flash` To disable go to `APBGame\Config` open `DefaultGame.ini` with Notepad and set `m_bEnableMuzzleFlash=true` to `m_bEnableMuzzleFlash=false`.
- `Player Ragdolls` To disable go to `APBGame\Config` open `DefaultGame.ini` with Notepad and set `m_nMaxDeadRagDollPawns=8` to `m_nMaxDeadRagDollPawns=0` and `m_bDeathAnimations=true` to `m_bDeathAnimations=false`.
- `Disk Cache` If you have low RAM and the game crashes often, turn it on. Go to `APBGame\Config` open `DefaultEngine.ini` with Notepad and set `m_bUseDiskCache=False` to `m_bUseDiskCache=True`.
- `Garbage Collection` If disabled the game may crash after a while and you will lose the ability to use some of the customization kiosks in Social, but at the price of eliminating stuttering during fights and respawning. Go to `Engine\Config` open `BaseEngine.ini` with Notepad and set `TimeBetweenPurgingPendingKillObjects=60` to `TimeBetweenPurgingPendingKillObjects=0`.

# How To Install
- Repair the game if you have previously used any other configs.
- Launch the game once before proceeding, then close it.
- Copy and Paste `APB Reloaded` inside your game installation path, usually located at `C:\Program Files (x86)\Steam\steamapps\common` or `C:\Program Files (x86)\GamersFirst`.
- Create a shortcut of APB.exe, you can find it inside the `Binaries` folder.
- Right-Click on the shortcut and go to `Properties`, under `Target` add `-nomovies -language=1031` at the end of the line.
- Example: `Target: "C:\Program Files (x86)\Steam\steamapps\common\APB Reloaded\Binaries\APB.exe" -nomovies -language=1031`.
- You must use this shortcut to launch the game every time, put it on your Desktop or in the Start Menu if you like, to do this press `WIN+R` and type `shell:common programs` then drag the shortcut inside the folder.
- Reinstall the configs every time you update or repair the game!

# Game Files Used
### [APBGame\Config]
- APBCompat.ini - Graphic Settings
- APBMachineOptions.ini - Game Options
- DefaultEngine.ini - Disable Notifications, Disable Disk Cache
- DefaultGame.ini - Low-Priority Emitters, Disable NPC Ragdolls, Disable Magazine Casings
- DefaultInput.ini - Keybinds
- DefaultUI.ini - Faster and more Stable UI, Reduced Chat Fading

### [APBGame\Content\Audio\DefaultMusicLibrary]
- defaultmusiclibrary.xml - Disable Default Music Library

### [APBGame\Localization\GER]
- APBUserInterface.GER - UI Messages
- ConsoleCommands.GER - Replaces /abandonmission with /a
- EmoteCommands.GER - Removes /dance and /strikea prefix from emotes
- HUDDistrictMapMarker.GER - Vehicle Name [• w •]
- HUDMessages.GER - HUD Messages and Killfeed
- Options.GER - Options Menu Description
- TaskObjectives.GER - Missions Description

### [Engine\Config]
- BaseEngine.ini - Engine Optimization, Disable Texture Streaming
