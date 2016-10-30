## pico8-rpg-game-template
This is a PICO-8 game template. Use it as a start point for your games.

This is inspired heavily by [pico8-game-template](https://github.com/misato/pico8-game-template).

So far this base template:
- Entities. X/Y coordinates are at the center of the sprite.
- Collision detection for solid tiles.
- A camera that follows an entity passed to it


One thing to note. Coordinates for entities are in tiles, not pixels. For example, 0,0 is the top most left tile. If you wanted to place a sprite at 64,64, your entity's x,y coordinates would be 8,8.
