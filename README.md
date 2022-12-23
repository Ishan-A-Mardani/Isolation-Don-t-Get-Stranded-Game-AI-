# Isolation or "Dont't Get Stranded" Game AI

## Rules
In this 2 player game, both players are given random initial spots which are also called safe spots. <br/>
Each player, during his/her chance, has to move 1 space in any of the 8 possible directions. <br/>
They cannot go on any of the already visited squares. <br/>
Both the players can go on either of the safe spots as many times as they want. <br/>
The motive of the game is to 'ISOLATE' the opponent such that he/she has no possible square that he/she can got to. <br/>

## Algorithm
This code file works on the minimax algorithm along with alpha-beta pruning. <br/>

Heuristic Score: ( Heuristic Score is the Scoring Algorithm based on which the minimax tree works ) <br/>
a * ( Number of possible moves the AI has )  -  b * ( Number of possible moves the Opponent has ) <br/>
a - Higher its value, more is the AI focussed on increasing the number of possible moves the AI has <br/>
b - Higher its value, more is the AI focussed on reducing the number of possible moves the Opponent has <br/>
