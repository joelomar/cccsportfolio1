# cccsportfolio1
# Guesser GAme
This is just a simple game for a portfolio project for Codecademy Carrer Path.

The game is call ‘Guesser’.

In this game, the player needs to guess a randomly generated number between 1 and 10.

In this game:
We import the random module to generate a random number.
The guess_number_game() function is defined to encapsulate the game logic.
Inside the function, a random number between 1 and 10 is generated using random.randint(1, 10) and stored in secret_number.
The game starts with a welcome message and instructions.
Inside the while loop, the player is prompted to enter their guess using input(), and the guess is converted to an integer using int().
The number of attempts is incremented.
The player’s guess is compared with the secret number, and appropriate messages are displayed based on whether the guess is too low, too high, or correct.
If the player’s guess matches the secret number, a congratulatory message is displayed along with the number of attempts, and the loop is exited using break.
After the loop ends, a closing message is displayed.
To play the game, run the guess_number_game() function. The program will interactively prompt you to enter your guesses until you guess the correct number.

Image:
![ghgfg](https://github.com/joelomar/cccsportfolio1/assets/7598467/f52c9760-e030-45f3-9d10-9a5da364af6f)
