# 21 wires: solution

Note that your battery, light bulb and small wires are basically a connection
tester.

At the bottom, leave wire `1` unconnected, connect `2` and `3` to each other,
connect `4`, `5`, `6` to each other, `7`-`10`, etc, so that we have connected
groups of sizes 1, 2, 3, 4, 5 and 6:

```
 1

 2 -  3

 4 -  5 -  6

 7 -  8 -  9 - 10

11 - 12 - 13 - 14 - 15

16 - 17 - 18 - 19 - 20 - 21
```

Now make a trip to the top (take both light bulb and the battery with you), and
figure out which letter is connected to nothing else (say: `G`). Then figure
out, which two letters are connected to each other, but nothing else (say: `K`
and `E`). Go on to find the connected group of three letters (`L`, `B` and
`R`), of four letters etc. Then, connect them like so:

```
 G
 |
 K    E
 |    |
 L    B    R
 |    |    |
 A    T    J    P
 |    |    |    |
 M    U    F    I    H
 |    |    |    |    |
 S    C    D    N    O    Q
```

Go back to the bottom (take your equipment), remove the original connections,
and figure out the connected groups. Together with the first measurement, this
is enough information to figure out all connections.

As an example, consider the letter `B`. In the first measurement (on the top),
we found out that it is connected to the group of three wires at the bottom
(`3`, `4` and `5`). Back at the bottom, we will find a group of five numbers
which are connected to `B`. *Exactly one* of these five numbers will be equal
to *either* `3`, `4` or `5` (say: `5`). We now know that `B` and `5` are
connected (`3` and `4` will appear in groups of four and six).

This solution works cleanly for any
[triangular number](https://en.wikipedia.org/wiki/Triangular_number)
of wires, but can be easily adapted to work for all natural numbers.
