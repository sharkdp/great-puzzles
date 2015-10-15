# Rational pirates: solution

It might be expected intuitively that Pirate A will have to allocate little if
any to A for fear of being voted off so that there are fewer pirates to share
between. However, this is quite far from the theoretical result.

This is apparent if we work backwards: if all except D and E have been thrown
overboard, D proposes 100 for D and 0 for E. D has the casting vote, and so
this is the allocation.

If there are three left (C, D and E) C knows that D will offer E 0 in the next
round; therefore, C has to offer E 1 coin in this round to win E's vote, and
get C's allocation through. Therefore, when only three are left the allocation
is C:99, D:0, E:1.

If B, C, D and E remain, B considers being thrown overboard when deciding. To
avoid being thrown overboard, B can simply offer 1 to D. Because B has the
casting vote, the support only by D is sufficient. Thus B proposes B:99, C:0,
D:1, E:0. One might consider proposing B:99, C:0, D:0, E:1, as E knows it won't
be possible to get more coins, if any, if E throws B overboard. But, as each
pirate is eager to throw each other overboard, E would prefer to kill B, to get
the same amount of gold from C.

Assuming A knows all these things, A can count on C and E's support for the
following allocation, which is the final solution:

* A: 98 coins
* B: 0 coins
* C: 1 coin
* D: 0 coins
* E: 1 coin

Also, A:98, B:0, C:0, D:1, E:1 or other variants are not good enough, as D
would rather throw A overboard to get the same amount of gold from B.

[More information on Wikipedia](https://en.wikipedia.org/wiki/Pirate_game)
