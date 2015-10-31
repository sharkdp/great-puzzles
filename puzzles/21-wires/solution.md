# 21-wires: solution

Note that your battery, light bulb and small wires are basically a connection tester, and that "connected" is an equivalence relation.

At the bottom, leave 1 unconnected, connect 2 and 3 to each other, connect 4-6 to each other, 7-10, etc, so that we have "equivalence classes" of connectedness of sizes 1, 2, 3, 4, 5 and 6.

Now make a trip to the top, and figure out which letters are connected to nothing else, to one other letter, to two others, etc, until you have figured out the equivalence classes.

Now connect the first letters from each equivalence class (there are 6 of them) in a new equivalence class, the second from each (5 of them) in another, etc. Go to the bottom, remove the original connections, and figure out the new equivalence classes in a similar manner.

We now know from the first set of classes what groups of n letters (for n=1 to 6) at the top correspond to what groups of n numbers at the bottom. From the second set of classes we now know which letters and numbers were the "first" in their original classes, which were the "second," etc, so we have the complete pairing.

This solution works cleanly for any triangular number of wires, but can be easily adapted to work for all natural numbers.
