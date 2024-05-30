# Lua Shooter Game

## Description
I created Lua Shooter Adventure for my A levels in computer science. This OOP game features multiple moving elements, where players shoot enemies, use items, gain powerups, and progress through waves. Enemies can drop powerups like instant kill and full ammo. The game includes scattered items, increasing enemy difficulty, enemy attacks, music, menus, and pause functionality.

## Key Features
- **Powerups**: Enemies can randomly drop powerups when they die, such as instant kill and full ammo, for the player to pick up.
- **Items**: The map contains scattered items like guns, health packs, and grenades that the player can pick up and use.
- **Wave System**: Enemies spawn in waves, becoming stronger and faster as the player progresses.
- **Enemy AI**: Enemies can shoot back at the player, adding to the challenge.
- **Audio and UI**: The game features music, a menu, and the ability for the player to pause the game.

## Detailed File Descriptions
### Lua Scripts
**weapon.script:**
Handles the logic for weapons used by the player, including shooting mechanics.

**weapon.go:**
Game object configuration for weapons.

**bullet.script:**
Manages bullet behavior, including movement and collision detection.

**bullet.go:**
Game object configuration for bullets.

**bulletFactory.script:**
Handles the creation and pooling of bullets.

**grenade.script:**
Manages grenade behavior, including explosion mechanics.

**grenade.go:**
Game object configuration for grenades.

**grenadeFactoryScript.script:**
Handles the creation and pooling of grenades.

**player.script:**
Handles player behavior, including movement, shooting, and health.

**player.go:**
Game object configuration for the player character.

### Assets
- **Images**: Sprites and textures for the player, enemies, items, and background.
- **Audio**: Background music and sound effects.

## Installation and Usage
1. **Clone the repository**:
   ```sh
   git clone https://github.com/osman789g/lua-shooter-adventure.git
   
2. **Navigate to the repository**:
   ```sh
   cd lua-shooter-game

3. **Running the project**:
   Open the 'game.project' file in a game development environment, such as Defold IDE.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries or feedback, please contact [osman.temirkhanov@gmail.com].
