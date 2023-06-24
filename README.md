# Mei Configs
- Discord: MeiRiver
- I have no responsibility for what may happen to your account if you use these Configs. Keep in mind these files are against the APB EULA however they are approved by Little Orbit!
- Feel free to add or remove any feature you like! ^.^

# Graphics
- Five graphic presets, choose one in the game options! Note: If you change preset while in game you must change district to make the changes effective. In some cases the game may crash!
- [Performance] The default preset. High FPS and low textures, useful for slower computers.
- [Low Shadows] Performance preset with low quality shadows.
- [Balanced] My personal choice! A good balance between performance and quality, useful for decent computers.
- [High Shadows] Balanced preset with high quality shadows.
- [Quality] Not recommended. Low FPS but incredible quality, useful for customizing cars, characters and clothes.

# Keybinds
- I have completely redone, sorted and optimized the structure of the keybinds, with many new ones too! You can customize any key from the game options.
- I recommend resetting all in-game keybinds to default after installing this configuration.
- Sprint (Inverted) - Reverse the Sprint key to make you Sprint endlessly, hold it down to walk. Goodbye pinky pain! Note: When you join a district press the key once to start Sprinting.
- Crouch (Hold) - Hold down the key to Crouch, release it to stand up. Makes movements faster and easier! Note: If you press Crouch and Jump at the same time you will get stuck in the Crouch position, press Jump again to - stand up.
- Grenade (Toggle) - Press the Grenade key once to start cooking it then press the Fire key to throw! Note: I suggest using it for Grenades only, while for Half-Bricks and Eight-Balls use the Grenade (Hold) key.
- Lean (Hold) - Hold down the key while aiming. Note: It's difficult to move around.
- Music Player - Right-Shift to Open the Music Player, Right-CTRL to Play/Pause, Arrow keys to change Tracks and adjust the Volume.
- Abandon Mission - Use to quickly abandon the mission.
- Alt+F4 - Ragequit :p

# Additional Notes
- Do NOT use the Advanced APB Launcher with these configs!
- You need to set the game language for the Localization to work, but don't worry, the game will stay in English.
- Bloom is turned off in the performance presets making the game very dark, you can adjust the brightness in the game options.
- Depending on your hardware you may want to enable Double Buffering in the game options, it will give you a significant FPS boost but it will also increase input latency.
- If you want to disable the Muzzle Flash go to [APBGame\Config] and open "DefaultGame.ini" with a Notepad, scroll all the way down and set "m_bEnableMuzzleFlash=true" to "m_bEnableMuzzleFlash=false".
- If your game stutters or crashes frequently try enabling Disk Cache, go to [APBGame\Config] and open "DefaultEngine.ini" with a Notepad, search for "m_bUseDiskCache=False" and change it to "m_bUseDiskCache=True".

# How To Install
- Repair the game if you have previously used any other configs.
- Launch the game once before proceeding, then close it.
- Copy and Paste "APB Reloaded" inside your game installation path, usually located at "C:\Program Files (x86)\Steam\steamapps\common" or "C:\Program Files (x86)\GamersFirst".
- Create a shortcut of APB.exe, you can find it inside the "Binaries" folder.
- Right-Click on the shortcut and go to "Properties", under "Target" add "-nomovies -language=1031" at the end of the line.
- Example: [Target: "C:\Program Files (x86)\Steam\steamapps\common\APB Reloaded\Binaries\APB.exe" -nomovies -language=1031].
- You must use this shortcut to launch the game every time, put it on your Desktop or in the Start Menu if you like, to do this press "WIN+R" and type "shell:common programs" then drag the shortcut inside the folder.

# Game Files Used
• [APBGame\Config]
- APBCompat.ini - Video Settings
- APBMachineOptions.ini - Video Settings
- APBUI.ini - Faster and more Stable UI
- DefaultEngine.ini - Disables Notifications, Disables Disk Cache
- DefaultGame.ini - Low-Priority Emitters, Disables NPC Ragdolls, Disables Magazine Casings
- DefaultInput.ini - Keybinds

• [APBGame\Content\Audio\DefaultMusicLibrary]
- defaultmusiclibrary.xml - Disables Default Music Library

• [APBGame\Localization\GER]
- APBUserInterface.GER - UI Messages
- ConsoleCommands.GER - Replaces /abandonmission with /a
- EmoteCommands.GER - Removes /dance prefix from any dance emote
- HUDDistrictMapMarker.GER - Vehicle Name [• w •]
- HUDMessages.GER - HUD Messages and Killfeed
- Options.GER - Options Menu Description
- TaskObjectives.GER - Missions Description

• [Engine\Config]
- BaseEngine.ini - Engine Optimization, Disables Texture Streaming
