# 100 prisoners

[![Source](https://img.shields.io/badge/Source-%E2%9C%93-green.svg)](https://en.wikipedia.org/wiki/100_prisoners_problem)
![Difficulty](https://img.shields.io/badge/Difficulty-hard-red.svg)

The director of a prison offers 100 prisoners on death row, which are numbered
from 1 to 100, a last chance. In a room there is a cupboard with 100 drawers.
The director puts in each drawer the number of exactly one prisoner in random
order and closes the drawers afterwards. The prisoners enter the room one after
another. Each prisoner may open and look into 50 drawers in any order and the
drawers are closed again afterwards. If during this search every prisoner finds
his number in one of the drawers, all prisoners are pardoned. If just one
prisoner does not find his number, all prisoners have to die. Before the first
prisoner enters the room, the prisoners may discuss their strategy, afterwards
no communication of any means is possible.


If every prisoner selects 50 drawers at random, the probability that a single
prisoner finds his number is 50%. Therefore, the probability that all prisoners
find their numbers is the product of the single probabilities which is
*(½)<sup>100</sup> ≈ 0.0000000000000000000000000000008*, a vanishingly small
number. The situation appears hopeless for the prisoners.

Can you find a (much) better strategy for the prisoners?

[See solution](solution.md)

Remark: While it is possible to come up with the correct answer without
advanced mathematics, you may need to write a small simulation or have
some knowledge about combinatorics to derive the exact probability for
winning.
