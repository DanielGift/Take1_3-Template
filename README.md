# Take1_3-Template
The game Take 1-3 is played as follows: A random number of stones is initially in a pot. Two players take turns removing 1, 2, or 3 stones at a time. The player to take the last stone wins.

First, you must determine the winning strategy in the game. Note that this stretegy will guarantee a win in some, but not all, scenarios.

Then, you should implement this winning strategy in the computerMove method. This method takes as an input the numebr of stones currently in the pot (it assumes the number remaining is > 0) and it returns the correct number of stones to take according to the winning strategy. If such a move is not possible, it returns a random number of stones to take.

Note that to get a random number between 1 and 3, you can use 
int rand13 = (int) (Math.random()*3.0) + 1;

Next, you should implement the humanMove method, which prompts the user to take a number of stones; If the move is valid, it returns the number of stones taken; otherwise, it displays an error message -- "You are allowed to only take 1, 2, or 3 stones" or "Can't take that many: only <nStones> left in the pile" -- and returns -1.

Finally, you should complete the play method. Most of it has ben done for you, but 3 wspecific lines need to be added. Descriptions are given in-line as to what these lines shoudl do.

