Number Guessing Game in Python
Overview:

The Number Guessing Game is a simple and engaging Python program where the player tries to guess a randomly generated number within a specified range. The game provides feedback to the player on whether their guess is too high, too low, or correct, and continues until the player guesses the correct number or opts to quit.

How It Works:

Game Setup:

The program starts by importing the necessary modules, such as random, to generate a random number.
It then defines the range within which the number will be generated (e.g., 1 to 100).
The player is prompted to enter their name and the game settings, such as the range of numbers and the maximum number of attempts allowed.
Game Loop:

A random number is generated within the specified range.
The player is given a certain number of attempts to guess the number.
For each guess:
The program checks if the guess is correct, too high, or too low.
Feedback is provided to the player based on the result of their guess.
The number of remaining attempts is updated and displayed.
The game ends when the player guesses the number correctly or exhausts all attempts.
End of Game:

If the player guesses the number correctly, they are congratulated and informed of the number of attempts used.
If the player runs out of attempts, the correct number is revealed, and the player is encouraged to try again.
An option to play again or exit the game is provided.
