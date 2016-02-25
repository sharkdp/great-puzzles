# Wizards and Dwarves: solution

The dwarves can devise a strategy that will cost the life of at most one dwarf.

Let black hats signify 1's and white hats signify 0's.
Each dwarf calculates the parity (sum modulo 2) of the hats in front of him.
The first (tallest) dwarf announces the color corresponding to the parity he calculated. He may or may not be killed (depending on his luck.Of course the Wizards can always engineer it so he dies, because they know this is the optimal strategy).

The next dwarf compares the parity he calculated and the parity the first dwarf announced. If the two parities are the same, that means his hat is white, otherwise it is black. He announces this color, and lives.

Each successive dwarf, armed with the original parity of all but the first dwarf and the colors of the hats of all the preceding dwarves (but the first), can easily calculate the color of his own hat. An inductive proof of correctness is pretty easy.

Thus only the first (and tallest) dwarf dies... which I guess explains why dwarves are so short. 