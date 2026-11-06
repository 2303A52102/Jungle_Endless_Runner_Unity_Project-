# Jungle_Endless_Runner_Unity_Project-
Jungle Endless Runner (Unity 3D)
A 3D jungle-themed endless runner game developed using Unity 3D and C# for Android and Windows PC. The player runs continuously through a beautiful and adventurous jungle environment, avoiding obstacles, collecting coins, and using special power-ups to achieve the highest score.

The game features a procedurally generated jungle environment, including trees, bushes, rocks, wooden bridges, rivers, vines, and other natural elements. The character, jungle environment, obstacles, coins, power-ups, UI, particles, and audio are generated procedurally, reducing the need for paid or external assets.
Status: The project is designed for Unity 2022.3 LTS. Compilation and play-testing should be verified inside Unity.

Requirements
- Unity 2022.3 LTS (project uses Unity 2022.3.62f1).
- Unity Hub.
- Android Build Support for Android deployment.
- Windows Build Support for Windows deployment.
- Built-in Render Pipeline, Legacy Input Manager and uGUI.
Quick start
1. Extract the project ZIP file.
2. Open Unity Hub.
3. Select Add Project from Disk.
4. Choose the extracted Jungle_Endless_Runner folder.
5. Open the project using Unity 2022.3 LTS.
6. Wait for Unity to compile the scripts.
7. Run the setup tool using Jungle Runner > 1. Run Full Project Setup, if available.
8. Open Assets/Scenes/Gameplay.unity or MainMenu.unity.
9. Press the Play button to start the game.
No manual GameObject creation or reference wiring is required if the project uses the same automatic GameBootstrap architecture.

Controls
Action	Windows PC	Android
Move left/right	Arrow keys, A/D	Swipe left/right
Jump	Up arrow, W, Space	Swipe up
Slide	Down arrow, S	Swipe down
Pause	Esc / P	Pause button

Gameplay summary
The game features an endless running experience through a dense and adventurous jungle environment.
- Auto-run: The player automatically runs forward through three lanes.
- Three-lane movement: Move left and right to avoid obstacles.
- Jump: Jump over rocks, fallen trees, wooden logs and other obstacles.
- Slide: Slide underneath hanging vines and low wooden barriers.
- Increasing speed: The running speed gradually increases to make the game more challenging.
- Procedural generation: Jungle paths, trees, bushes, obstacles and environmental objects are generated dynamically.

- Obstacles
The player must avoid different obstacles throughout the jungle journey.
1. Fallen trees – Jump over fallen tree trunks.
2. Large rocks – Avoid rocks placed on the running path.
3. Thorny bushes – Change lanes to avoid thorny plants.
4. Wooden barriers – Jump over wooden obstacles.
5. Hanging vines – Slide underneath hanging vines.
6. Tree roots – Avoid large roots across the path.
7. River gaps – Jump over gaps in the jungle pathway.
8. Animal obstacles – Avoid obstacles such as logs or other jungle hazards.

Power-ups
Power-up	Function
Magnet	Attracts nearby coins for 10 seconds.
Shield	Protects the player from one collision.
Speed Boost	Increases running speed and destroys obstacles.
Score x2	Doubles the score for a limited time.
Coin Bonus	Instantly adds 25 coins.

Scoring system
- Distance travelled increases the score.
- Coins collected provide additional points.
- Power-ups help the player achieve higher scores.
- High score and best distance are saved using PlayerPrefs.
- Players can revive after game over using collected coins, subject to the configured revive limit.
