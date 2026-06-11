# High-Low Arcade Game 🎯

A fun, interactive command-line number-guessing game built with Python. The game challenges you to guess a randomly generated number between 1 and 100, featuring retro ASCII art screens for wins and losses!

## 🎮 How to Play

The objective is simple: guess the secret number before you run out of lives.

1. **Pick a Difficulty:** Choose between `'Easy'` or `'Hard'` mode.
   * **Easy Mode:** Gives you **10 attempts** to find the number.
   * **Hard Mode:** Gives you only **5 attempts** for a real challenge.
2. **Make Guesses:** Input your guess when prompted. The game will tell you if the secret number is **Higher!** or **Lower!** than your guess.
3. **Win or Lose:** Guess correctly to unlock the 🏆 **Legendary Win Screen**. Run out of attempts, and it's 💀 **Game Over**!

## 📂 Code Highlights

The project is completely self-contained within a single file:
* **Dynamic Scoping:** Uses a custom recursive game loop function (`highlow()`) to track your guesses and remaining lives.
* **Built-in Visuals:** Features massive multiline ASCII art layouts for the game's title branding, victory screen, and failure screen.

## 🛠️ How to Run the Game Locally

1. Make sure you have Python installed on your machine.
2. Clone this repository to your computer:
   ```bash
   git clone [https://github.com/Neha-reddy-c/High-Low.git](https://github.com/Neha-reddy-c/High-Low.git)
3. Move into the project directory::
   ```bash
   cd High-Low
4. Run the script::
   ```bash
   python3 HighLow.py
