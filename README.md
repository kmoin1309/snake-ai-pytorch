<h1>Abstract</h1>
<p>The Snake Game with AI project merges the classic Snake game with artificial intelligence (AI) algorithms, introducing an innovative twist to the traditional gaming experience. Stemming from the era of early arcade games, Snake has retained its popularity over the years, serving as a timeless favorite for gamers and programmers alike due to its simplicity and addictiveness.
 
In this project, we aim to reimagine the Snake game by integrating AI techniques to control the snake's movements. By doing so, we explore the convergence of gaming and AI, offering a platform for experimentation and learning in both domains. Leveraging Python programming and the Pygame library, we develop an interactive game environment where players can engage with the snake while also witnessing the capabilities of AI algorithms in action.
 
This abstract provides a succinct overview of the project's objectives, highlighting the fusion of gaming and AI, and underscoring the educational value of the endeavor. Through the implementation process, we navigate the intricacies of game development and AI programming, addressing challenges and exploring opportunities for further innovation.</p>

<h1>Data models:</h1>
 
Game Board Data Model:
• The game board is typically represented as a grid of cells.
• Each cell can have different states such as empty, containing the Snake, or containing food.
• The dimensions of the grid determine the size of the game world.
 
Snake Data Model:
• The Snake is represented as a collection of segments or body parts.
• Each segment has a position on the game board (coordinates) and a direction of movement.
• The Snake's body forms a linked list or array, with each segment referencing the next segment in the Snake's body.
• Action
[1,0,0]->straight
[0,1,0]->right turn
[0,0,1]->left turn
 
Food Data Model:
• Food items are represented by their position on the game board.
• Each food item has coordinates within the grid.
 
AI Agent Data Model:
• The AI agent's data model includes its internal representation of the game state.
• This representation may include features such as the positions of the Snake and food, as well as other relevant information.
• Depending on the AI algorithm used, the agent's data model may also include neural network weights, Q-values, or other learned parameters.
• Rewards:
eat food: +10
game over: -10
else:0
 
Game State Data Model:
• The game state encapsulates the current state of the game, including the positions of the Snake, food, and any other relevant elements.
• State:
[danger straight, danger right, danger left,
direction left, direction right, direction up, direction down,
food left, food right, food up, food down]
 
• Example:
[anger straight, danger right, danger left,
direction left, direction right, direction up, direction down,
food left, food right, food up, food down]
so:
[0,0,0,
0,1,0,0,
0,1,0,1]
