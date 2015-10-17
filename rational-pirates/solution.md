# Rational pirates: solution

The oldest pirate will propose a *97, 0, 1, 0, 2* split (he gets 97 coins) and
win the vote 3:2.

[Alternative solution: *97, 0, 1, 2, 0* split.]

## Explanation

This can be solved by working backwards.

Let the pirates be *A > B > C > D > E*, with *A* being the oldest.

* 2 Pirates *D E*: Remember that *E* wants to survive, maximize the number of
gold coins *and* throw as many other pirates overboard as he possibly can.
Consequently, no matter what *D* proposes, *E* will *always* vote against him.

* 3 Pirates *C D E*: Pirate *C* will propose a *100, 0, 0* split. The voting
result will be *Y Y N*. Remember that pirate *D* will die if he votes no, so he
will be in favor of this split.

* 4 Pirates *B C D E*: Pirate *B* will propose a *98, 0, 1, 1* split. The
voting will be *Y N Y Y*. Both *C* and *E* will vote in favor of this split
because they would get 0 coins otherwise.

* 5 Pirates *A B C D E*: Pirate *A* will propose a *97, 0, 1, 2, 0* split. The
voting will be *Y, N, Y, Y, N*. Again, *A* can win the vote by giving pirate
*C* and pirate *D* one more coin than they would receive otherwise. (Instead
of winning the vote of pirate *D*, he could also win the vote of pirate *E*,
leading to the alternative solution).
