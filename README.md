<p align="center">
  <a href="https://www.gamersfirst.com/apb/"><img alt="APB Reloaded" width=50% src="https://static.wikia.nocookie.net/logopedia/images/5/5a/APB_Reloaded.png"></a>
  <br>
  Mei Configs
  <br>
  <a href="https://github.com/MeiRiver/Mei-Configs/archive/refs/heads/APB.zip">Download</a>
</p>
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://cdn.prod.website-files.com/6257adef93867e50d84d30e2/636e0b544a3e3c7c05753bcd_full_logo_white_RGB.png">
    <source media="(prefers-color-scheme: light)" srcset="https://cdn.prod.website-files.com/6257adef93867e50d84d30e2/636e0b50aa9e99958d574a23_full_logo_black_RGB.png">
    <img alt="Discord" width=10%>
  </picture>
  <br>
  MeiRiver
</p>

# About
**These are my personal configuration files. After many requests I decided to release them here with some new features.  
They have been tested for months and should work as expected, but if you find any problems please contact me on Discord.  
Feel free to add or remove any feature you like ^.^**

> [!CAUTION]
> **I have no responsibility for what may happen to your account if you use my Configs.  
> Keep in mind that editing game files is against the Terms of Service (ToS) however these Configs are approved by Little Orbit!**

# How To Install
> [!IMPORTANT]
> **Repair the game if you previously had used any other configs.  
> Reinstall the configs whenever you update or repair the game.**

1. **Copy and Paste `APB Reloaded` inside your game installation path, usually located at `C:\Program Files (x86)\Steam\steamapps\common` or `C:\Program Files (x86)\GamersFirst`**
2. **Create a shortcut of APB.exe, you can find it inside the `Binaries` folder.**
3. **Right-Click on the shortcut, go to `Properties` find `Target` and add `-nomovies -language=1031` at the end of the line.**
4. **Example `Target: "C:\Program Files (x86)\GamersFirst\APB Reloaded\Binaries\APB.exe" -nomovies -language=1031`**
5. **Press `WIN+R` and type `shell:common programs` then drag the shortcut inside the folder, now you can launch APB from the Start Menu.**
6. **From now on you must use this shortcut every time you launch the game.**

# Graphics
**There are Five graphic presets, choose one from the game options. Characters and Player Vehicles are in high quality for all presets.  
If you swap preset while playing you must change district to make some changes effective.**
|Preset|Quality|Shadows|FPS|
|:---:|:---:|:---:|:---:|
|Performance|LOW|NONE|HIGHEST|
|Low Shadows|LOW|LOW|HIGH|
|Balanced|HIGH|NONE|MEDIUM|
|High Shadows|HIGH|HIGH|LOW|
|Quality|ULTRA|ULTRA|LOWEST|

# Settings
|Name|Default|Description|
|:---:|:---:|:---:|
|Resolution|1920x1080|Ultra-Low resolutions are now available in the game options.|
|Smooth Frame Rate|ON|Enabled: Framerate is capped at 128 to avoid an issue known as Sliding.<br>Disabled: Framerate is uncapped.<br>If you want a custom FPS cap go to `Engine\Config` open `BaseEngine.ini` with Notepad and set `MaxSmoothedFrameRate=128` and `MaxClientFrameRate=0` to your desired values.|
|Double Buffering|OFF|Depending on your hardware you may want to enable it in the game options.<br>It will give you a significant FPS boost but at the cost of an increased input latency.|
|Bloom|ON|To keep the transparent background without the Bloom effect make sure this is enabled in the game options then go to `Engine\Config` open `BaseEngine.ini` with Notepad and put `;` before `DefaultPostProcessName=APBPostEffectMaterials.APBPostEffect_Process`|
|Muzzle Flash|ON|To disable go to `APBGame\Config` open `DefaultGame.ini` with Notepad and set the following line:<br>`m_bEnableMuzzleFlash=true` >>> `m_bEnableMuzzleFlash=false`|
|Player Ragdolls|ON|To disable go to `APBGame\Config` open `DefaultGame.ini` with Notepad and set the following two lines:<br>`m_nMaxDeadRagDollPawns=8` >>> `m_nMaxDeadRagDollPawns=0`<br>`m_bDeathAnimations=true` >>> `m_bDeathAnimations=false`|
|NPC Ragdolls|OFF|To enable go to `APBGame\Config` open `DefaultGame.ini` with Notepad and set the following five lines:<br>`m_cfg_fMinNPCRagdollDisplayTime=0.0` >>> `m_cfg_fMinNPCRagdollDisplayTime=60.0`<br>`m_cfg_fMaxNPCRagdollDisplayTime=0.0` >>> `m_cfg_fMaxNPCRagdollDisplayTime=120.0`<br>`m_cfg_nMaxNumberOfNPCRagdolls=0` >>> `m_cfg_nMaxNumberOfNPCRagdolls=30`<br>`m_cfg_nHardMaxNumberOfNPCRagdolls=0` >>> `m_cfg_nHardMaxNumberOfNPCRagdolls=45`<br>`m_cfg_fMinNPCRagdollDespawnDelay=0.0` >>> `m_cfg_fMinNPCRagdollDespawnDelay=10.0`|
|Login Screen|OFF|Decrease loading time by making the Login Screen black. You can't create new characters when disabled.<br>To enable go to `APBGame\Config` open `DefaultEngine.ini` with Notepad and set the following two lines:<br>`Map=UIDistrict_DistrictSelect.apb` >>> `Map=APBLoginLevel.apb`<br>`LocalMap=UIDistrict_DistrictSelect.apb` >>> `LocalMap=APBLoginLevel.apb`|
|Disk Cache|OFF|Turn it on if you have low RAM and the game crash too often.<br>To enable go to `APBGame\Config` open `DefaultEngine.ini` with Notepad and set the following line:<br>`m_bUseDiskCache=False` >>> `m_bUseDiskCache=True`|
|Garbage Collection|ON|When disabled the game may crash often if you have low RAM and you will be unable to use some of the customization kiosks in Social, but at the price of eliminating stuttering during fights and respawning.<br>To disable go to `Engine\Config` open `BaseEngine.ini` with Notepad and set the following line:<br>`TimeBetweenPurgingPendingKillObjects=60` >>> `TimeBetweenPurgingPendingKillObjects=0`|

# Keybinds
**I have sorted and optimized the structure of the keybinds, with many new ones too! You can customize any key from the game options.  
I recommend resetting all of the game's keybinds to defaults after installing the configs and then changing them back to your preferences.**
|Name|Description|
|:---:|:---:|
|Sprint (Inverted-Jog)|Reverse the bind to make you Sprint endlessly, hold it down to Jog. When you join a district press the key once to start Sprinting.|
|Sprint (Inverted-Walk)|Reverse the bind to make you Sprint endlessly, hold it down to Walk. When you join a district press the key once to start Sprinting.|
|Crouch (Hold)|Hold down the key to Crouch, release it to stand up. If you press Crouch and Jump at the same time you will get stuck in the Crouch position, press Jump again to stand up.|
|Grenade (Toggle)|Press the Grenade key once to start cooking it then press the Fire key to throw. I suggest using it only for Grenades, while for Half-Bricks and Eight-Balls use the `Grenade (Hold)` bind.|
|Lean (Hold)|Hold down the key while aiming. It's difficult to move around when you use it.|
|Scoreboard (Hold)|Hold to display the Scoreboard. Can be used to quickly close the inventory menu after changing weapons.|
|Map (Hold)|Hold to show the Map. Can be used to quickly close the inventory menu after changing weapons.|
|Abandon Mission|Use to quickly abandon the mission.|
|Music Player|Right-Shift to Open the Music Player, Right-CTRL to Play/Pause, Arrow-Keys to change Tracks and adjust the Volume.|
|Social|Open customization kiosks in Social. They are Character Customisation, Clothing Customisation, Vehicle Customisation, Symbol Editor, Music Studio.|
|ALT+F4|**RAGEQUIT**|

# Localization
- **`Missions Description` Stages are displayed immediately at the start of the mission instead of the default description.**
- **`Missions Equipment` The name of the Equipment needed is shown next to the mission title. Blue is for Enforcers, Red is for Criminals.**
- **`Emotes` Simplified the Emotes commands by removing `/dance` and `/strikea` prefixes.**

> [!NOTE]
> **To use my Localization you have to add the launch argument `-language=1031` to your APB Shortcut.  
> [Read How](#how-to-install)**

# Disabling UI Elements
**Go to `APBGame\Config` open `DefaultEngine.ini` with Notepad and put `;` before any of these strings.**

- **Top Left**
  - **`Notoriety Level` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_HUD_Heat"**
  - **`Pledged Contact` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_HUD_Contact"**
  - **`Dirty Money` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_HUD_OpenWorld"**
  - **`Fight Club Challenges` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_HUD_Challenges"**
  - **`Daily Activities` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_HUD_DailyActivities"**
  - **`Team/Group List` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_HUD_Group"**

- **Top Right**
  - **`Money` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_HUD_Cash"**
  - **`Weapons/Ammo/Reload/Resupply` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_HUD_WeaponInfo"**
  - **`Grenades/Carried/Stored Items` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_HUD_Cargo"**
  - **`Killfeed` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_HUD_ActionMessage"**
  - **`Activable/Consumable Modifications` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_HUD_Usables"**

- **Bottom Left**
  - **`Bounty/Killsteak/Winstreak Notifications` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_HUD_Ceremony"**
  - **`Mail Icon` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_HUD_Mail"**

- **Bottom Right**
  - **`Radar` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_HUD_Radar"**
  - **`Witness Icon` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_HUD_Witnessing"**
  - **`Clock` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_HUD_Clock"**

- **Center**
  - **`Crosshair/Hitmarker` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_HUD_Reticule"**
  - **`Radial Hit Indicator` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_HUD_HitIndicators"**
  - **`Objectives Progress Circle` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_HUD_CSAProgressBars"**
  - **`Kill/Assist/Arrest/Stun/Medal/Objective Messages` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_HUD_CombatMsgs"**
  - **`PlayerInfo/CarInfo/RamRaidInfo` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_HUD_InfoBrowser"**
  - **`Health Indicator` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_HUD_Health"**
  - **`Ranks/Weapons (Killfeed)/Money ($)/Joker TIckets Icons` +GlobalDataStoreClasses="APBUserInterface.cUIDataStore_APBImages"**

# Game Files Used
- **[APBGame\Config]**
  - DefaultCompat.ini - Graphic Settings
  - DefaultEngine.ini - Disable Bounty/Killsteak/Winstreak Notifications, Disable Disk Cache, Disable Login Screen Background
  - DefaultGame.ini - Sound Emitters Priority, Disable NPC Ragdolls, Disable Magazine Casings Particles
  - DefaultInput.ini - Keybinds
  - DefaultMachineOptions.ini - Game Options, Video Settings
  - DefaultUI.ini - Faster UI, Reduced Chat Fading

- **[APBGame\Content\Audio\DefaultMusicLibrary]**
  - defaultmusiclibrary.xml - Disable Default Music Library

- **[APBGame\Localization\GER]**
  - APBUserInterface.GER - UI Messages
  - EmoteCommands.GER - Remove /dance and /strikea prefixes from Emotes
  - HUDDistrictMapMarker.GER - Vehicle Name [• w •]
  - HUDMessages.GER - HUD Messages and Killfeed
  - MissionTemplates.GER - Missions Equipment
  - Options.GER - Options Menu Description
  - TaskObjectives.GER - Missions Description

- **[Engine\Config]**
  - BaseEngine.ini - Engine Optimization, Disable Texture Streaming
