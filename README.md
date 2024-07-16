# Snake and ladder game
A web-based implementation of the classic Snakes & Ladders board game. The game can be played by one player against an automated opponent.
## Demo
You can play the game [here](https://snakelad.netlify.app/).
## Features
- Play Snakes & Ladders against an automated opponent
- Animated movement of pieces
- Random dice rolls
- Display of player's turn and winner

  ## Technologies Used
- HTML5
- CSS3
- JavaScript
- [GSAP (GreenSock Animation Platform)](https://greensock.com/gsap)
  
## Implementation
### Project Features
1. **Animated Movement:** Smooth animations for player movements using GSAP.
2. **Random Dice Rolls:** Randomized dice rolls to determine player moves.
3. **Player Display:** Shows which player's turn it is and the winner.
4. **Obstacles Handling:** Snakes and ladders are implemented with automatic movement when a player lands on them.

### Future Extensions
1. **Multiplayer Mode:** Allow multiple human players to play together.
2. **Scoring System:** Implement a scoring system to track wins and losses over multiple games.
3. **Leaderboard:** Display a leaderboard for high scores.
4. **Sound Effects:** Add sound effects for dice rolls and player movements.
5. **Mobile Compatibility:** Optimize the game for mobile devices.

   
  ## Setup
To run this project locally, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/Akshat577/snake-and-ladder.git
    ```

2. **Navigate to the project directory:**
    ```sh
    cd snakes-and-ladders
    ```

3. **Open `index.html` in your browser:**
    ```sh
    open index.html
    ```
    or you can use any code editor with live server extension to run the project.

 ## Usage
### How to Play
1. Open the game in your browser.
2. Click on the dice to roll.
3. Your piece will move according to the number rolled.
4. If you land on the bottom of a ladder, you'll move up to the top of the ladder.
5. If you land on the head of a snake, you'll slide down to the tail of the snake.
6. The first player to reach square 100 wins.

### Controls
- **Roll Dice:** Click on the dice image to roll.
- **Play Again:** Click on the "Play Again" button after the game ends.

## Acknowledgements
- [GSAP](https://greensock.com/gsap) for animations.
- [FontAwesome](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css) for icons.
  
