# Blue eyes: solution

This solution also comes from [xkcd.com](http://xkcd.com/solution.html).

The answer is that on the 100th day, all 100 blue-eyed people will leave.

If you consider the case of just one blue-eyed person on the island, you can
show that he obviously leaves the first night, because he knows he's the only
one the Guru could be talking about. He looks around and sees no one else, and
knows he should leave. So: [**THEOREM 1**] If there is one blue-eyed person, he
leaves the first night.

If there are two blue-eyed people, they will each look at the other. They will
each realize that "if I don't have blue eyes [**HYPOTHESIS 1**], then that guy
is the only blue-eyed person. And if he's the only person, by **THEOREM 1** he
will leave tonight." They each wait and see, and when neither of them leave the
first night, each realizes "My **HYPOTHESIS 1** was incorrect. I must have blue
eyes." And each leaves the second night.

So: [**THEOREM 2**]: If there are two blue-eyed people on the island, they will
each leave the 2nd night.

If there are three blue-eyed people, each one will look at the other two
and go through a process similar to the one above. Each considers the two
possibilities -- "I have blue eyes" or "I don't have blue eyes." He will know
that if he doesn't have blue eyes, there are only two blue-eyed people on the
island -- the two he sees. So he can wait two nights, and if no one leaves, he
knows he must have blue eyes -- **THEOREM 2** says that if he didn't, the other
guys would have left. When he sees that they didn't, he knows his eyes are
blue. All three of them are doing this same process, so they all figure it out
on day 3 and leave.

This induction can continue all the way up to **THEOREM 99**, which each person
on the island in the problem will of course know immediately. Then they'll each
wait 99 days, see that the rest of the group hasn't gone anywhere, and on the
100th night, they all leave.
