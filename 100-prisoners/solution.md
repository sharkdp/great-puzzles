# 100 prisoners: solution

See the Wikipedia page for the
[100 prisoners problem](https://en.wikipedia.org/wiki/100_prisoners_problem)
for a very good description of the solution (or see the summary below).

See also: a [description of the puzzle](https://www.youtube.com/watch?v=eivGlBKlK6M)
by MinutePhysics on YouTube and the
[explanation of the solution](https://www.youtube.com/watch?v=C5-I0bAuEUE).

---

Surprisingly, there is a strategy which gives the prisoners a survival
probability of more than 30%. The key to success is that the prisoners do not
have to decide beforehand which drawers they are going to open. Each prisoner
can use the information gained from the contents of previously opened drawers
to help him decide which drawer to open next. Another important observation is
that this way the success of one prisoner is not independent of the success of
the other prisoners.

In order to describe the strategy, not only the prisoners, but also the drawers
are numbered from 1 to 100, for example row by row starting with the top left
drawer. The strategy is now as follows:

1. Each prisoner first opens the drawer with his own number.
2. If this drawer contains his number he is finished with his search and was
   successful.
3. Otherwise, the drawer contains the number of another prisoner and he next
   opens the drawer with this number.
4. The prisoner repeats steps 2 and 3 until he finds his own number or has
   opened 50 drawers.

This approach ensures that every time a prisoner opens a drawer he either finds
his own number or the number of another prisoner he has not encountered so far.

