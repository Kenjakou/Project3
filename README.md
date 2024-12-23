Tower Defense Game 
The source code and assets for a simple Tower Defense game built using Unity. The objective is to strategically place towers to defend against waves of enemies and prevent them from reaching the end point. The game incorporates features like tower upgrades, challenging enemy waves, and a scoring system to enhance gameplay.

Key Features:
  Tower Placement:
  
    Players can position different types of towers at designated locations on the map to stop waves of enemies.

  Variety of Towers:
  
    Choose from multiple tower types, each with unique abilities such as slowing enemies, dealing damage over time, or creating splash damage for strategic depth.

  Enemy Waves:
  
    Enemies spawn in waves with progressively increasing difficulty, featuring varied health, speed, and behaviors.

  Tower Upgrades:
  
    Enhance towers to boost their effectiveness, such as increasing damage, range, or special effects.

  Scoring System:
  
    Earn points for defeating enemies, which can be spent on placing and upgrading towers.

  Visual Effects:
  
    Enjoy dynamic effects for attacks, enemy destruction, and tower upgrades, adding to the immersive experience.

How to Play:

Start the Game: Click the "Play" button in Unity to begin.

Place Towers: Use the interface to select and place towers on the map. Towers will automatically attack enemies within range.

Defend the Path: Strategically position towers to prevent enemies from reaching the goal.

Upgrade Towers: Earn points by defeating enemies and use them to upgrade your towers for enhanced performance.

Survive Waves: Protect the path against increasingly difficult enemy waves. The game ends if enemies reach the goal.


Gameplay Mechanics:

  Towers:
  
    Automatically target and attack enemies within range.
    Can be upgraded to improve damage, attack speed, or range.
    
  Enemies:
  
    Follow predefined paths toward the goal.
    Possess unique health and speed attributes, with tougher enemies appearing in later waves.
    
  Waves:
  
    Composed of multiple enemy groups with escalating difficulty.
    Players must manage resources efficiently to counter each wave.
    
  Resources:
  
    Earned by defeating enemies.
    Used for placing and upgrading towers.
    Technologies Used
    
Unity: Game engine for development and execution.

C#: Programming language for game logic.

UI System: For menus, tower placement, and heads-up display (HUD).

NavMesh: Unity’s navigation system for enemy pathfinding.

Particle Effects: For visual enhancements like tower attacks and enemy destruction.


Project Structure:

  Assets:
    
    Scripts: Includes C# scripts for tower behavior, enemy movement, wave management, etc.
    Prefabs: Contains prefabricated objects like towers, enemies, and the environment.
    Scenes: Includes the primary game scene with the map and UI elements.
    Materials: Textures and materials for game visuals.
    UI: Assets for interface elements such as buttons, health bars, and score displays.
      
  Scripts:
  
    Tower.cs: Defines tower attributes and actions.
    Enemy.cs: Handles enemy health, movement, and behaviors.
    WaveManager.cs: Manages the spawning and pacing of enemy waves.
    GameManager.cs: Oversees the game state, scoring system, and win/lose conditions.
    UIManager.cs: Controls interface elements like tower placement, score display, and game over screens.

Contributing:

  Contributions are welcome! You can contribute by,
    Introducing new tower types and enemy behaviors.
    Enhancing graphics or animations.
    Expanding gameplay mechanics, such as adding more tower upgrade options.
    To contribute, open an issue or submit a pull request. Let’s make this project even better!
