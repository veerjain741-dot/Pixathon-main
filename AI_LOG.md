Pixathon Project:

Game name: Maze Shift
Date: 23 October 2026

##Tools used:

chat gpt, antigravity, 

##key prompts:

1. Build a complete, playable browser game called Maze Shift, inspired by pac-man.
  Technology Use: plain HTML, CSS, and JavaScript. Put the entire game in a single index.html file.   
  Do not require external libraries, APIs, images, or assets. Make it playable immediately in the browser.

  Core gameplay: Display a grid-based maze with walls, a player, and collectible pellets.
  Move the player with the arrow keys or WASD. The player must collect every pellet to win.
  Walls block movement, and the player must never walk through walls.
  Every 10 seconds, the maze shifts to another of 3 predefined layouts.
  When the maze shifts, some walls change position, forcing the player to rethink their route.
  
  Keep the player and all remaining pellets in valid walkable cells after every shift.
  Never trap the player inside an enclosed area. Show a countdown until the next maze shift.
  Display the player's score, remaining pellets, and game status. Include a restart button and clear win/game-over screens.
  
  Design: Use a dark arcade-style background, a bright contrasting player, clearly visible walls, and glowing pellets.
  Make the game look polished and fun, with smooth movement and simple animations.
  Show the instructions on the start screen. Make the layout fit a normal desktop browser window.
  Important: Prioritize reliable gameplay over visual complexity. Ensure the player cannot collect pellets through walls.
  Ensure maze shifts do not put walls on the player or pellets. Do not leave any placeholder functions or unfinished features.
  After generating the code, explain how to run it and list the main tests I should perform.
  Start by building the complete working game, then help me fix any bugs I discover. 



2nd prompt: gave feedback to the AI on 7 pointers


1. yes movement is fine and walls block it from phasing.
2. pellet collection is fine and no issue there .
3. countdown is fine and progress bar is working. warning sound working. closing gates are shown in advance, and the player doesnt get stuck. warp sound is played, and layout is switched with the walls reconfiguring well. 
4. yes that seems to be working and no issues with player getting stuck.
5. ghosts are stuck in the middle box (their spawn) and not moving at all so that seems to be a major issue. i myself had to go to the spawn and die, so that part is working. and game over animation with the score and pellets left is working
6. is working properly 

so i think main issue is the ghosts not working at all, i can just see them but their movement is negligible


3rd prompt:

