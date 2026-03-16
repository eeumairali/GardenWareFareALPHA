# GardenWareFareALPHA

A garden warfare game built by Andy and Umair as a hands-on project for learning Unity at an advanced level. This project covers core game-development concepts including terrain design, player and enemy mechanics, game management, and animations.

---

## Game Development Steps

### Step 1 — Create Terrain & Environment
- Create and sculpt the terrain using Unity's terrain tools
- Apply ground textures and surface materials for a realistic look
- Place environmental objects (trees, rocks, fences, props)
- Design the overall world layout and level boundaries

### Step 2 — Make Player
- Create the player character model and set up its prefab
- Implement movement controls (WASD / joystick input)
- Add a camera that smoothly follows the player
- Add basic interactions (shooting, picking up items, triggering events)

### Step 3 — Make Enemy
- Create the enemy character model and set up its prefab
- Implement simple AI behaviour (patrol, chase, attack states)
- Add an enemy spawning system with configurable spawn points and rates
- Set up combat interaction between the player and enemies (hit detection, damage)

### Step 4 — Make Game Manager
- Create a `GameManager` script to act as the central controller
- Track and display the player's score
- Implement a health system for the player and enemies
- Define win and lose conditions (e.g., eliminate all enemies, player health reaches zero)
- Manage overall level state (start, pause, restart, game-over)

### Step 5 — Add Animations
- Import character and object animation clips into Unity
- Create an Animator Controller for each animated object
- Hook up player animations (idle, walk, run, shoot, die)
- Hook up enemy animations (idle, patrol, attack, die)
- Add animations for interactive objects (doors, pickups, explosions)

---

## About

| Field | Detail |
|-------|--------|
| Engine | Unity |
| Genre | Garden Warfare (Third-Person Shooter) |
| Purpose | Advanced Unity learning project |
| Developers | Andy & Umair |

