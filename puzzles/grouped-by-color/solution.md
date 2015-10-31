# Grouped by color: solution

All dwarves are able to stand in one line, sorted by color, if they follow this
strategy:

The first dwarf picks a random place. The second dwarf picks another random
place, far away from the first dwarf.

Any following dwarf:
- If all the other dwarves' hats are the same color, he stands on either side
  (far away)
- If he sees blue and red hats, he chooses a position between the two groups.

This way, the dwarfs are always lines up as blue first, red next (or vice
versa).
