
# Guess the Number

## Description
"Guess the Number" is a simple and fun Python-based game where the computer randomly selects a number, and the player has to guess it within a limited number of attempts. The game provides helpful hints, telling the player if their guess is too high or too low, and tracks how many attempts the player has made.

## Features
- **Random Number Generation:** The computer generates a random number from 1 to 100.
- **Player Input:** Players input their guesses via the console.
- **Hint System:** Feedback is provided to help the player, indicating if the guess is too high, too low, or correct.
- **Attempts Tracking:** Players are given 7 attempts to guess the number correctly, with the game showing how many attempts are left.
- **Game Over Messages:** If the player doesn't guess correctly in 7 tries, the game ends, revealing the correct number.
- **Time Complexity:** O(log2n), where n is the range between the lower and upper bound (100 in this case).
- **Space Complexity:** O(1), as the variables used are constant and no additional memory is required.

## How to Play
1. Run the Python script.
2. The program will generate a random number between 1 and 100.
3. You will be prompted to enter your guesses one by one.
4. After each guess, the program will let you know if your guess is too high, too low, or correct.
5. You have 7 attempts to guess the number correctly.

### Example
- The random number is 42.
- You guess 50: The game will tell you, "Your guess is higher."
- You guess 25: The game will say, "Your guess is lower."
- Keep narrowing down until you find the correct number or run out of attempts!

## Future Enhancements
- **Graphical User Interface (GUI):** A future version could use Tkinter or PyQt to build a graphical version of the game.

## Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/nivedhapm/Guess-the-number.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Guess-the-number
    ```
3. Run the Python script:
    ```bash
    python main.py
    ```


