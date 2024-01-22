# so_long
Simple 2D game.
This is a project from 42 Heilbronn.

To play the game, compile with "make", then run with "./so_long map.ber". You can also choose other maps or make your own. See below for map rules.

Controls:
The W, A, S, and D keys will be used to move the main character.
Pressing ESC closes the window.

Map rules:
- The map description file must have the .ber extension
- The map must be composed of only 5 possible characters: 0 for an empty
space, 1 for a wall, C for a collectible, E for map exit and P for the player’s
starting position.
- The map must be closed/surrounded by walls, if not the program must return an error.
- Map must have at least one exit, one collectible, and one starting position.
- The map must be rectangular.

This is a simple valid map:

<img width="96" alt="image" src="https://github.com/K-isikoglu/so_long/assets/135221950/174b9db9-2aef-4ba4-a4fd-c1b0ef8f7106">

