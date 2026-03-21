# The World Beyond Us

_The World Beyond Us_ is a 2025 puzzle game created by a team of four who competed in the University of Florida's Open Source Club Mini Hack-a-Thon. Developed in Roblox Studio, this narrative-driven game implements artificial intelligence into puzzles with a story about a sentient robot.

[Link to Roblox Game](https://www.roblox.com/games/130502028716320/The-World-Beyond-Us)

## Controls

- WASD for movement
- E to pull up tablet display

## Game Visuals

![First cutscene displaying main area of laboratory](gifs/Play_Credits_1.gif)
![Second cutscene displaying puzzle game involving user input to move a ball](gifs/Play_Credits_2.gif)
![Third cutscene displaying player's spawnpoint aka bedroom](gifs/Play_Credits_3.gif)

## Puzzles[^1]

[^1]: Puzzles can be played in any order!

### Puzzle 1: Navigating a Ball with Prompts

This puzzle lets the player control a ball by typing directions into a text box! Rather than moving the ball with standard controls, players type natural language commands describing where or how they want the ball to move. A ChatGPT-powered API processes these commands and converts it into a Vector3 object that will be used to drive the ball’s movement based on the player's input.

![Gameplay of AI-powered ball puzzle](gifs/Ball_1.gif)
![Gameplay of AI-powered ball puzzle](gifs/Ball_2.gif)

### Puzzle 2: Sorting Items Based on Categories

This puzzle asks the player to sort items into their correct categories while an TV powered by the same ChatGPT API observes and learns from their actions! As players organize items, the AI collects data to "train" itself and reports to the player what it has observed so far.

![Gameplay of AI-powered sorting items puzzle](gifs/Sorting_1.gif)
![Gameplay of AI-powered sorting items puzzle](gifs/Sorting_2.gif)<br>
<sub>(second gif has smaller framerate to showcase AI response)</sub>
