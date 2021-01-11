# Bingo Simulation Math IA

## This program will simulate a set of bingo games.

#### The input for the program is a list in which each element will contain one of two things

First: The number of games
Second: The number of players per game

For example if the list was as follows:
`[
[100000, 1],
[100000, 10],
[100000, 100],
[100000, 1000],
[100000, 10000]
]`

First 100,000 games with 1 player will be simulated
Then 100,000 games with 10 players
and so on so forth until 100,000 games with 10,000 players have been simulated

By default the values above are what will run when running the program

To change the values edit the simulation.py program and change the variable "gameVals" on line 132

The program will output two files to the tmp folder: A json file with the data, and an excel file with the same data just in a more readable format

Currently the tmp folder holds a run of the default gameVals, so the values used to make Figure 5 in the table are stored there.

The program will also print how long every tenth of a set takes, and how long the whole program took to run, just for timekeeping purposes.
