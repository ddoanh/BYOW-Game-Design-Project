# BYOW: Game Design Project

## Description:
This project asks to design and implement a 2D tile-based world exploration engine. By “tile-based”, we mean the worlds you generate will consist of a 2D grid of tiles. By “world exploration engine” we mean that your software will build a world, which the user will be able to explore by walking around and interacting with objects in that world.
https://youtu.be/UQarjseWlzU

## Featues:
Once the program is launched, a menu window will be displayed.
![Screen Shot 2023-01-31 at 12 25 27 AM](https://user-images.githubusercontent.com/98563830/215707787-947f5237-201c-46b8-bbf0-a804dffcae39.png)
Options:
  - Press 'N' or 'n' to start a new game.
  - Press 'L' or 'l' to load a saved game.
  - Press 'Q' or 'q' to quit the game.

After selecting a new game, another window will be displayed, asking the user to enter a seed. The seed is a positive number up to 9,223,372,036,854,775,807 and is used by the random generator to generate a unique game world. That means that if you enter the same seed, the identical world be generated.
![Screen Shot 2023-01-31 at 12 25 55 AM](https://user-images.githubusercontent.com/98563830/215707850-60779791-1d1d-4722-985f-f3d16a927bbb.png)

Once the seed is entered, press 'S' or 's' to generate the world. Innitially, the world exists with no light
![Screen Shot 2023-01-31 at 12 26 12 AM](https://user-images.githubusercontent.com/98563830/215707873-2d08665e-bcc1-48db-827b-baa6eb509720.png)

After turning on the light by pressing 'P', the world exists ore clearly which consists of uniquely generated rooms and corridors connecting them together. Various items are randomly generated around the map.
![Screen Shot 2023-01-31 at 12 26 29 AM](https://user-images.githubusercontent.com/98563830/215707901-6192c7ed-2ae6-44ad-b1e7-c5c17166319a.png)
![Screen Shot 2023-01-31 at 12 26 55 AM](https://user-images.githubusercontent.com/98563830/215707946-524e18cc-40e3-4c60-832c-c274bf738bfc.png)

## Game controls
  - 'W', 'A', 'S', 'D' – Movement of player around the world
  - 'Q' – Quit the game. The game is saved and can be loaded from the main menu.

