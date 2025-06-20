# Rock Paper Scissors Game

A simple interactive Rock Paper Scissors game built with JavaScript.  
The game keeps track of your wins, losses, and ties using the browser's local storage, allowing you to continue your game progress even after refreshing the page.

---

## Features

- Play Rock, Paper, or Scissors against the computer.
- Score tracking with wins, losses, and ties saved in `localStorage`.
- Play using buttons or keyboard shortcuts (`r` for rock, `p` for paper, `s` for scissors).
- Auto-play mode that plays a game every second automatically.
- Visual feedback with emojis representing player and computer moves.

---

## How to Play

1. Click the **Rock**, **Paper**, or **Scissors** button, or press the keyboard keys:
   - `r` for Rock
   - `p` for Paper
   - `s` for Scissors
2. The computer randomly selects a move.
3. The result (`You win`, `You lose`, or `Tie`) is displayed.
4. Your score updates and is saved in your browser’s local storage.
5. Click the **Auto Play** button to start or stop the game playing automatically every second.

---

## Usage

The main JavaScript logic is in `script.js`. Key functions include:

- `playGame(playerMove)`: Plays a round based on the player's move.
- `pickComputerMove()`: Randomly chooses the computer’s move.
- `updateScoreElement()`: Updates the score display on the page.
- Auto-play uses `setInterval` to repeatedly play rounds every second.

---

## Screenshots

*Include screenshots here of your game interface and gameplay for better presentation.*

---

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/rock-paper-scissors.git


## Rock Paper Scissors Game

Open `index.html` in your browser.

Enjoy playing!

---

## Technologies Used

- JavaScript (ES6)  
- HTML5  
- CSS3  
- Browser localStorage API  

---

## Future Improvements

- Add animations for moves.  
- Add multiplayer or online mode.  
- Improve UI/UX design.  
- Add sounds for interactions.  

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Author

Ellias Sithole – [GitHub Profile](https://github.com/BabaKaElijah)

