# battleshipslite
A simpler version of battleships, where:

- all the "ships" are 1x1
- you have three ships
- the computer has three ships
- it's a 5x5 map that looks something like this:

[0, 1, 2, 3, 4, 5]
[1, 0, 0, 0, 0, 0]
[2, 0, 0, 0, 0, 0]
[3, 0, 0, 0, 0, 0]
[4, 0, 0, 0, 0, 0]
[5, 0, 0, 0, 0, 0]

(except it's a grid!)


1) You first are given the opportunity to type in the three co-ordinates for your ships i.e
1,1
2,2
3,3
[0, 1, 2, 3, 4, 5]
[1, 8, 0, 0, 0, 0]
[2, 0, 8, 0, 0, 0]
[3, 0, 0, 8, 0, 0]
[4, 0, 0, 0, 0, 0]
[5, 0, 0, 0, 0, 0]
The ships are plotted on the map as the number 8.

2) You then have the opportunity to guess where the enemy ships are, by typing in your first coordinate to fire.
i.e 1,5
If you miss, it will say "There are still more enemy ships, keep firing."
If you hit, it will say "You have sunk a ship!"

3) The computer will then pick coordinates.
Then the computer will check to see whether it's already tried those coordinates before, and if not, it will fire.
It will let you know if it sinks one of your ships.

Repeat.
Whoever hits and sinks all three ships wins.

