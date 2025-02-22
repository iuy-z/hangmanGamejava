# hangmanGamejava
Hangman Game 🎮
A simple Hangman Game built in Java that allows users to guess words while keeping track of their attempts.

How It Works 🛠️
Welcome Message:

The game welcomes the player and prompts them to enter their name.
Word Selection:

The program randomly selects a word from a predefined list of words stored in a 2D array.
Game Rules:

The player has 6 attempts to guess the correct word.
The game displays underscores (_) for each letter in the word.
The player enters one letter at a time to guess the word.
Game Mechanics:

If the guessed letter is correct, it replaces the underscore _ in the word.
If the guessed letter is incorrect, the number of remaining attempts decreases.
The game displays a Hangman figure after each incorrect guess.
Winning & Losing Conditions:

If the player guesses all letters correctly, they win the game. 🎉
If the player runs out of attempts, they lose the game. ❌
Game Records:

The program keeps track of the player's name, guessed word, and game status (win/loss).
Play Again Option:

The player is given an option to play again or exit the game.
Key Features ✨
✅ Randomly selects words from a predefined list
✅ Tracks user attempts and displays the remaining tries
✅ Visual representation of the Hangman
✅ Checks for duplicate guesses to prevent repeated inputs
✅ Game data storage to record the number of games played

Code Breakdown 🧑‍💻
1. Main Game Loop
The game runs inside a while loop that continues until the player chooses to exit.
2. Word Selection
getRandomword() and getRandomword1() select a random word from the wordslist array.
3. User Input Handling
The program takes a single-character input from the user and checks if it's in the word.
4. Updating Guessed Letters
updateGuessedLetter() updates the word display if the guessed letter is correct.
5. Checking Game Status
areWordsGUESSED() checks if all letters have been guessed.
6. Displaying Hangman
displayHangman() prints the Hangman figure based on the number of incorrect guesses.
7. Storing Game Records
gameRecord() stores and displays the player's name, guessed word, and game status.

 Prerequisites:
Install Java (JDK 8 or later)

Follow the on-screen instructions to guess the word.
Future Improvements 🚀
🔹 Add difficulty levels (Easy, Medium, Hard)
🔹 Implement score tracking and leaderboard
🔹 Use GUI for a better visual experience

This README will help users understand your game before running it! Let me know if you need any modifications. 🚀









