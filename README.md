Battle: A Turn Based Pokemon Style Game

To get the game up and running, you can type this into the Command Prompt:

git clone git@github.com:richarddewit/battle.git
cd battle
./run.py

Or if you want a Computer to fight a Computer(no input):

./run.py --auto

TODO
 Make "Computer vs Computer" a flag instead of a hardcoded boolean
 Separate messages into a Message class
 Generalize random move selection

GOAL
Write a simple game that lets the user and the computer take turns selecting moves to use against each other. Tthe computer and the player should start out at the same amount of health, and should be able to choose between the three moves:

The first move should do moderate damage and has a small range.
The second move should do a large range of damage and can deal high or low damage.
The third move should heal whoever selects it a good amount.

After each move, a message should be printed out that tells the user what just happened and how much health both the player and computer have. When health reaches 0, the game should end.
