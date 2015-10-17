# Blindfolded tricks: solution, part 2

Take one die from the group on the right and move it to the group on the left.
Then, flip the remaining 4 dice of the right group upside-down.

## Explanation

As given in the problem, if the left group sums to *k*, then the right group
sums to *28−k*. If you take a die *b* from the right group and move it
to the left, then the new sums are *k+b* and *28−k−b*. Now, because
the opposite sides of a single die always add to 7, any time you flip a
set of 4 dice summing to *x*, you end up with a set of 4 dice summing to
*28−x*. Therefore, if we flip all of the dice in the right group, we now
have: *28−(28−k−b)=k+b* which is the same value that we have on the left
side.
