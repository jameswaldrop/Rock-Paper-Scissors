
Rock Paper Scissors Game.
This is a Python program that allows you to play the Rock Paper Scissors game against different computer players. The program has several different player modes, including:

Random: the computer player chooses its move randomly each round.
Reflect: the computer player reflects the move of the other player in the previous round.
Cycle: the computer player cycles through the moves of rock, paper, and scissors each round.
Repeat: the computer player always selects rock.
Human: the player inputs their move for each round.
The program has a Player base class that all other player classes inherit from. The Game class handles the game logic, while the beats function determines if player one's move beats player two's move.

To start the game, run the program and select a player mode. Then enter the number of rounds you want to play. The program will play the game, round by round, and keep track of the score until the game is over. At the end of the game, the final scores will be displayed, and the winner will be announced.

To run the program, you need to have the following modules installed:

random
time
colorama
The colorama module is used to display text in different colors.
