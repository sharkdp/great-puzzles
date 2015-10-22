# Rational pirates: solution

The oldest pirate will propose a *98, 0, 1, 1* split (he gets 98 coins) and win
the vote 3:1.

## Explanation

This can be solved by working backwards.

Let the pirates be *A > B > C > D*, with *A* being the oldest.

* 2 Pirates *C D*: Remember that *D* wants to survive, maximize the number of
gold coins *and* throw as many other pirates overboard as he possibly can.
Consequently, no matter what *C* proposes, *D* will *always* vote against him.

* 3 Pirates *B C D*: Pirate *B* will propose a *100, 0, 0* split. The voting
result will be *Y Y N*. Remember that pirate *C* will die if he votes no
(because he will end up in the 2 Pirates situation from above), so he will be
in favor of this split.

* 4 Pirates *A B C D*: Pirate *A* will propose a *98, 0, 1, 1* split. The
voting will be *Y N Y Y*. Both *C* and *D* will vote in favor of this split
because they would get 0 coins otherwise.

## Alternative versions

See the following sources for variants of this puzzle:

* https://de.wikipedia.org/wiki/Pirate_game Five pirates and a different
  voting resolution (in case of a tie, there is a casting vote). This leads
  to a different solution.
* https://en.wikibooks.org/wiki/Puzzles/Logic_puzzles/Gold_Coins Same voting
  resolution as here, but it is not clearly stated if they are bloodthirsty
  or not.
