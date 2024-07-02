# 1️⃣ AKEBI

<details>

<summary><strong><code>PLAYER</code></strong></summary>



### <mark style="color:yellow;">**God Mode**</mark> <a href="#god-mode" id="god-mode"></a>

* God Mode - Includes immortality against almost any type of damage.
*   **`Conditional`** - includes conditional immortality.

    > Minimum Health - minimum % health to enable immortality.

    > Missing Attack Rate- Enemies with the specified % miss you.

### <mark style="color:yellow;">**Infinity Stamina**</mark> <a href="#infinity-stamina" id="infinity-stamina"></a>

* Enabled - enables infinite stamina mode
* Move Sync Packet Replacement - prevents packets from being sent to the server when using infinite endurance.

### <mark style="color:yellow;">**Cooldown Effects**</mark> <a href="#cooldown-effects" id="cooldown-effects"></a>

* Max Burst Energy - removes the need to reload your ulta.
* Reduce Skill/Burst Cooldown - reduces the delay before using the hedgehog.
* No Sprint Cooldown - removes the delay between sprints.
* Instant Bow Change - removes the cooldown of bow draw for archers.

### <mark style="color:yellow;">**No-Clip**</mark> <a href="#no-clip" id="no-clip"></a>

* Enabled - activates the function.
* No Animation - disables flight animation.
* Run on water - adds the ability to move on water. Speed - adjusts the speed of movement in flight mode.
* Camera-relative movement - moves the character in flight mode relative to the camera (where the player is looking, not the avatar).
* Allow movement in a blocked area - adds the ability to walk outside the red zone without bringing the character back.
* Alternate No-Clip - allows you to increase flight speed when CTRL is held down.
* Velocity mode - uses speed instead of movement position.
* Freedflight mode - does not remove collisions with textures. Use Custom Keys - enables your own hotkeys.

### <mark style="color:yellow;">**Attack Effects**</mark> <a href="#attack-effects" id="attack-effects"></a>

* Enabled - enables the function.
*   **`Multi-Hit Mode`** - Enables multiplier of your attacks.

    > OnePunch - you always kill the enemy with 1 hit.

    > Randomize Multiplier - adds a setting with a multiplier selection from min to max. Multiplier - multiplier of the number of attacks.
* Multi-Target - attacks targets within a radius of your choice
* Multi-Animation - enables multiple animations.
* Attack Speed - the attack speed (you can set your own value).
*   **`Custom Element`** - allows you to change the damage type of the element.

    > Random Element Type

    > Element Type
* Auto weakspot - always attacks at vulnerable spots.
* Critical Hit - constant crit attacks.

### <mark style="color:yellow;">Auto Run</mark> <a href="#auto-run" id="auto-run"></a>

* Enabled - enables the function.
* Speed - set the speed of the autorunner.

</details>

<details>

<summary><strong><code>WORLD</code></strong></summary>



### <mark style="color:yellow;">Auto Loot</mark> <a href="#auto-loot" id="auto-loot"></a>

* Auto pickup - automatically picks up items
* Auto disable when bag is full - disables pickup when inventory is full
* Delay Time (ms) - min 100ms - delay before pickup
*   Range - selection radius

    Range (m) - max 250m
*   Simulates human - selection delay simulation

    Delay range +(ms)
*   **`Auto Treasue`** - chest filter

    > Chest Filter, Chests, Leyline, Search Points, Quests Interacts, Others
*   **`Pickup Filters`** - item filter

    > Pickup Filter, Animals, Drop Items, Resources, Oculus

### <mark style="color:yellow;">Auto Tree Farm</mark> <a href="#auto-tree-farm" id="auto-tree-farm"></a>

* Enabled - enables automatic tree mining
* Attack Delay (ms) - delay between attacks
* Repeat Delay (ms) - delay between attacks on one tree
* Attacks per Tree - number of attacks per tree
* Range (m) - range

### <mark style="color:yellow;">Auto Destroy Object</mark> <a href="#auto-destroy-object" id="auto-destroy-object"></a>

* Enabled - includes automatic destruction of objects
*   **`Filters`**

    > Entity, Ores, Plants, Shields, MonsterShielded, Abyss mage bubbles, Doodads

    **`Special Entity`**

    > Sakura Bloom, Sand Pile, Chests, Special object, Romaritime Flowers, Dadelion Seed
* Range (m)

### <mark style="color:yellow;">Auto Puzzle</mark> <a href="#auto-puzzle" id="auto-puzzle"></a>

* Auto Puzzle - involves doing puzzles
*   **`Puzzle Items`** - list of puzzles that can be automatically executed

    > Seelie, Torch Puzzle, Elemental Monument, Floating Anemo Slime, Lighting Strike Probe, Bloatty Floatty, Large Rock Pile, Small Rock Pile, Sumery Puzzle, Dendro Granum, Stone Pillar Seal, Dendro Rock, Dendro Pile, Pressure Plate, The Withering, Unique Rocks, Oozing Concretions, Windmill Mechanism, Campfire Torch, Electric Conduction, Ancient Rime, Strange ice, Hydro Lamps, Geo Puzzle, Pirate Helm
* Delay Time (ms) - speed of execution
* Range (m) - max 100m - execution radius

### <mark style="color:yellow;">Skip Enchance Animation</mark> <a href="#skip-enchance-animation" id="skip-enchance-animation"></a>

* Enabled - includes the skip elevation of weapons or artifacts
* Show Level-Up Dialog For Substat Rolls - shows dialogs when artifacts update a characteristic

### <mark style="color:yellow;">Auto Talk</mark> <a href="#auto-talk" id="auto-talk"></a>

* Enabled - enables automatic dialogs
* Use Hotkey mode - hotkeys
* Auto-select Dialog - automatic selection of dialogs
* Exclude Katheryne/Tubby/Wagner - removes the automatic dialog selection
*   **`Fast Dialog`** - dialog speed

    > Time Speed - max 40
* Skip Cutscenes - skips cutscenes
* Skip Game Cutscenes - skips in-game cutscenes (created by the game)
* Skip Tutorial Page - skips the tutorial prompts

### <mark style="color:yellow;">Kill Aura</mark> <a href="#kill-aura" id="kill-aura"></a>

* Enable Kill Aura - enables Kill Aura
* Crash Damage Mode - enables damage type with attacks
*   **`Percent mode`** - mod percentage

    > Damage Value - damage values, Crash Attack Delay (ms) - delay between attacks, Crash Repeat Delay (ms) - delay to damage on the same monster
* Instant Death Mode - instant kill
* Kill Range (m) - max 100m - killing radius
* Only Hostile/Aggro - attack only triggered enemies

### <mark style="color:yellow;">Status Aura</mark> <a href="#status-aura" id="status-aura"></a>

* Enable
*   **`Filters`**

    > Entities, Common Monsters, Elite Monsters, Boss Monsters, Animals, Element List, All Element Selected
* Range (m) - max 150m

### <mark style="color:yellow;">Auto Challenge</mark> <a href="#auto-challenge" id="auto-challenge"></a>

* Enabled - includes completing challenges
* Auto Start - enables automatic start of Challenges
  * Start Range (m) - max 50m
* Auto Completion - automatic completion of challenges
  * Completion Range (m) - max 250m
* Delay (ms) - min 1000ms (1sec)

### <mark style="color:yellow;">Mob Vacuum</mark> <a href="#mob-vacuum" id="mob-vacuum"></a>

*   **`Enabled`** - includes the attraction radius of mobs

    > Entities, Common, Elite, Boss, Droppers, Pick-ups, NPCs
* Instant Vacuum - instant mob attraction
* Only Hostile/Aggro - pull in only triggered mobs
* Remove Collider - remove collision from mobs

### <mark style="color:yellow;">Fake Time</mark> <a href="#fake-time" id="fake-time"></a>

* Enabled - includes fake time
* Time hour
* Time minute
* Sync to server

### <mark style="color:yellow;">Game Speed</mark> <a href="#game-speed" id="game-speed"></a>

* Enabled - includes acceleration of the world (visually)
* Hotkey mode
* Multiplier (s) - max 6 sec

### <mark style="color:yellow;">Spawn Object</mark> <a href="#spawn-object" id="spawn-object"></a>

* Enabled - includes spun objects
  * Hotkey
  *   **`Object List`**

      > Gadget, Alchemy Table, Forging

      **`NPC`**

      > Ahangar, Aoi, Blanche, Chef Mao, Chen the Sharp, Dongsheng, Enteka, Euphraise, Granny Shan, Hajime, Hamawi, Herbalist Gui, Hertha, Jinwu, Katerina, Khalid, Kimiya, Lambad, Madarame, Marjorie, Master Zhang, Mikoshi, Ms. Yu, Sara, Schulz, Shimura, Timaeus, Tomoki, Verr Goldet, Wagner, Xingxi, Yayoi

### <mark style="color:yellow;">Fast Combine</mark> <a href="#fast-combine" id="fast-combine"></a>

* Enabled - includes automatic resource creation
  * HotKey
* Items count
* Custom ItemID

### <mark style="color:yellow;">Auto Activate Teleport</mark> <a href="#auto-activate-teleport" id="auto-activate-teleport"></a>

* Enabled - enables automatic activation of teleports
* Delay Time (ms)
* Distance (m) - max 300m
* Extra function - unique features
  *   **`Full teleport unlock`** - activates teleports with the specified delay

      > Delay (ms)
      >
      > Begin teleports unlock
  *   **`Full towers unlock`** - activates archon statues (instantly)

      > Unlock only current map - opens teleports only on the current map (locations like the abyss will not be opened)
      >
      > Unlock towers

### <mark style="color:yellow;">Worship Statue</mark> <a href="#worship-statue" id="worship-statue"></a>

* Enabled - surrenders oculus statues to archons (if they are already open)
  * Hotkey
  *   **`Status Worship`**

      > Anemoculus
      >
      > Dendroculus
      >
      > Electroculus
      >
      > Geoculus
      >
      > Hydroculus

### <mark style="color:yellow;">Auto Fish</mark> <a href="#auto-fish" id="auto-fish"></a>

*   Enabled

    > Catch Delay (ms)
*   Recast Rod

    > Recast Delay (ms)
*   Fish vacuum

    > Vacuum point radius
    >
    > Vacuum speed

### <mark style="color:yellow;">Auto Dungeon</mark> <a href="#auto-dungeon" id="auto-dungeon"></a>

* Enabled - automatic dungeons for artifact farming
* Insta Kill
* Delay
* Interpolation Speed
* Condense Resin

### <mark style="color:yellow;">Claim Level</mark> <a href="#claim-level" id="claim-level"></a>

* Enabled - automatically collects rewards from Katerina for leveling up.
  * Hotkey

### <mark style="color:yellow;">Take Achievements</mark> <a href="#take-achievements" id="take-achievements"></a>

* Enabled - activate the ability to pick up all rewards from achievements by clicking on any one achievement.

</details>

<details>

<summary><strong><code>TELEPORTS</code></strong></summary>

### <mark style="color:yellow;">Chest Teleport</mark> <a href="#chest-teleport" id="chest-teleport"></a>

* TP HotKey - hotkey for teleportation.
* Show Info - shows information to the nearest chest.
* Chest Filter - customizable filter of chests you need and their types.
* Show Chest - the tab shows the list of the nearest chests.

### <mark style="color:yellow;">Oculi Teleport</mark> <a href="#oculi-teleport" id="oculi-teleport"></a>

* TP HotKey - hotkey for teleportation.
* Show Oculi - the tab shows the list of nearest oculi.

### <mark style="color:yellow;">Map Teleport</mark> <a href="#map-teleport" id="map-teleport"></a>

* Enabled - enables the function.
* Use transport position - enables the hotkey through which you will be teleported on the map.
* Open the map, press the key, click on a point and you will be teleported to this point.
* Override Height (m) - overwrites the height and teleports to the given values if it can't find it.

### <mark style="color:yellow;">Custom Teleport</mark> <a href="#custom-teleport" id="custom-teleport"></a>

* Enable - enables the function.
* Custom Teleport - window that shows the list of teleportation points you have loaded.
* Add Custom Teleport - allows you to add your own teleport points, with their names, descriptions and coordinates.
  *   **`Custom Teleport Settings`** - window with customization of custom teleport points.

      > Browse - specify the path to the folder with teleports (teleports created by you will also be saved there).
      >
      > Reload - reloads the folder with teleports.
      >
      > Open Folder - opens the selected folder
      >
      > Auto select on load - selects the first teleport from the list when loading.
      >
      > Auto check all on load - checks all teleports on load.
      >
      > Json Multiply points - loads your json teleports by copying their contents and pasting them into the specified field.
* Hotkey - selection of hotkeys through which you can enable, stop, select specified teleportation types, reload teleport list.
* Enable Interpolation - allows you to move your character on the map by dragging him to the currently selected coordinate.
* Fast Teleportation - type of teleportation with instantaneous moving of the character to the specified coordinate with gradual loading of the terrain (does not work until Auto Preform is enabled).
* Auto Perform - the main function and type of teleportation with terrain loading (the timer stops on the loading screen when the terrain is loaded).
* Delay Time (s) - pause of moving between points.

### <mark style="color:yellow;">Quest Teleport</mark> <a href="#quest-teleport" id="quest-teleport"></a>

* QuestTP - enables the ability to teleport to the active quest (does not teleport to quests that have a search radius)
* Hotkey - enables the hotkey you will use to teleport using QuestTP.
* Fast Teleportation - type of teleportation with instantaneous movement of the character to the specified quest.

</details>

<details>

<summary><strong><code>ESP</code></strong></summary>

### <mark style="color:yellow;">ESP</mark> <a href="#esp-1" id="esp-1"></a>

* Enabled - enables ESP function
*   **`Other settings`** - window with other ESP settings

    > Calculate ESP Count - calculates the number of found objects in the area.
    >
    > Draw Name - displays the name of the object.
    >
    > Draw Distance - displays the distance to the object.
    >
    > Draw Health - displays the health of the object.
* Draw Mode - Box, Rectangle, CornerBox
* List Tracer - Line, OffscreenArrows
* Range (m) - parameter regulating the ESP range.
*   **`Fill Box`** - fills the found object with one color.

    > Fill Transparency - parameter regulating transparency.
* Middle Screen Tracer - lines go from the center of the screen.

### <mark style="color:yellow;">Font Settings</mark> <a href="#font-settings" id="font-settings"></a>

* Font Size - parameter regulating the font size.
* Font Outline - parameter regulates the line font.

### <mark style="color:yellow;">Global Color</mark> <a href="#global-color" id="global-color"></a>

* Box Color
* Tracer Color
* Rect Color
* Global Font Color

### <mark style="color:yellow;">Filters</mark> <a href="#filters" id="filters"></a>

* Filters with all subjects, entities and objects

</details>

<details>

<summary><strong><code>VISUAL</code></strong></summary>

### <mark style="color:yellow;">Custom Weather</mark> <a href="#custom-weather" id="custom-weather"></a>

* Enabled - includes the ability to change the weather
* Water Status
*   **`Weather type`**

    > CleartSky, Cloudy, Foggy, Storm, RainHeavy, FountainRain, SnowLight, EastCoast
* Lightning

### <mark style="color:yellow;">FPS Unloack</mark> <a href="#fps-unloack" id="fps-unloack"></a>

* FPS Limit - removes the fps limit
* FPS Limit - adds a limit on fps

### <mark style="color:yellow;">Other</mark> <a href="#other" id="other"></a>

* Show Chest Indicator - shows indicators of the nearest chests
* Show Skill Cooldowns - shows the cooldowns of skils
* No fog - removes fog
* Hide UI - removes interface
* Enable Peeking - removes blurring when you look under the character
* Paimon Follow - paimon always flies near you
* Grass Remove - removes grass

### <mark style="color:yellow;">Custom Profile</mark> <a href="#custom-profile" id="custom-profile"></a>

* Custom Profile
* UID
* NickName
* Level
* Exp
* World Level
* Avatar Image
* Card image

### <mark style="color:yellow;">Browser</mark> <a href="#browser" id="browser"></a>

* Enabled
* Url
* Width
* Height

### <mark style="color:yellow;">Camera Zoom</mark> <a href="#camera-zoom" id="camera-zoom"></a>

* Fov Changer

### <mark style="color:yellow;">Texture changer</mark> <a href="#texture-changer" id="texture-changer"></a>

* Enabled
* Head
* Body
* Dress
* Glider

### <mark style="color:yellow;">Anim-Emo Changer</mark> <a href="#anim-emo-changer" id="anim-emo-changer"></a>

* Animation
* Emotion
* Phoneme
* AppleKey
* ResetKey

### <mark style="color:yellow;">Skin Modifier</mark> <a href="#skin-modifier" id="skin-modifier"></a>

### <mark style="color:yellow;">Flycloak Modifier</mark> <a href="#flycloak-modifier" id="flycloak-modifier"></a>

* Enabled
* Flycloak Type

### <mark style="color:yellow;">Monster Modifier</mark> <a href="#monster-modifier" id="monster-modifier"></a>

* Enabled
* Monster List

</details>

<details>

<summary><strong><code>SETTINGS</code></strong></summary>

### <mark style="color:yellow;">Language</mark> <a href="#language" id="language"></a>

* English
* Chines
* TW/HK
* Vietnamese
* Russia

### <mark style="color:yellow;">Status Window</mark> <a href="#status-window" id="status-window"></a>

* Show Status Window
* Move Status Window
* Padding in status window

### <mark style="color:yellow;">Info Window</mark> <a href="#info-window" id="info-window"></a>

* Show Info Window
* Move Info Window
* Compact view

### <mark style="color:yellow;">FPS Indicator</mark> <a href="#fps-indicator" id="fps-indicator"></a>

* Show FPS Indicator
* Move FPS Indicator

### <mark style="color:yellow;">Protection</mark> <a href="#protection" id="protection"></a>

* Spoof Anticheat result
* Disable Protection
* User predifined file signature

### <mark style="color:yellow;">Custom Theme</mark> <a href="#custom-theme" id="custom-theme"></a>

* Show Style Editor
* Theme Select

### <mark style="color:yellow;">Fast Exit</mark> <a href="#fast-exit" id="fast-exit"></a>

* Enabled

### <mark style="color:yellow;">Danger Section</mark> <a href="#danger-section" id="danger-section"></a>

* Enable danger functions

### <mark style="color:yellow;">Other</mark> <a href="#other-1" id="other-1"></a>

* Cheat Menu Key (F1)
* Font Size
* Show Notifications
* Console Logging
* File Logging

</details>

<details>

<summary><strong><code>DEBUG</code></strong></summary>

### <mark style="color:yellow;">Task query</mark> <a href="#task-query" id="task-query"></a>

### <mark style="color:yellow;">Entity Manager</mark> <a href="#entity-manager" id="entity-manager"></a>

### <mark style="color:yellow;">Position</mark> <a href="#position" id="position"></a>

### <mark style="color:yellow;">Map Manager</mark> <a href="#map-manager" id="map-manager"></a>

### <mark style="color:yellow;">FPS Graph</mark> <a href="#fps-graph" id="fps-graph"></a>

</details>
