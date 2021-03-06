---
layout: post
title: "Perspectives: An Introduction"
---

In this post I want to kick off a series on my favorite problem-solving technique: 
Changing the way you look at a problem. Many commonly-used techniques
across a wide range of applications are essentially instances of perspective shifts,
but in my opinion the technique doesn't get enough love from problem-solvers. If this
isn't a core part of your repertoire,
it should be. There are many ways to do this, and many classes of problems that can
be simplified this way, but I will start off with a general overview to give some
motivation on why it is so useful.

When solving a problem, there is a lot of implicit bias in the way that we look at it.
If I were to pose a problem involving running on a moving walkway,
we may think a different way than if the problem instead involved the distance between
two trains moving
on the same track, or somebody throwing a baseball while skydiving, even though at a basic
level these
are all <i>the same problem</i> of adding velocities. There is no fundamentally "correct"
way
to think about any particular problem, in the sense that there are many equally valid
ways of looking at it. If I threw a paper airpline while riding a bicycle on top of a
moving walkway on a satellite orbiting Venus, what is the velocity of the airplane? There
is no one correct answer, it depends on your frame of reference. From my point of view,
the paper airplane isn't moving that quickly, but this is not the case for someone on the 
surface of Venus, which is again different than what someone on Earth would tell us.
None of these observers are lying; they all have valid (but different) answers based on
their perspective on the problem. However, not all perspectives are equally useful: In many cases
a problem that appears intractible in one view becomes trivial in another. This should
be a familiar concept to anyone who has used u-substitution in calculus (or anyone who has
tried to calculate the velocity of a paper airplane from the frame of reference of a different
planet).

As an example, let's look at the four bugs (or mice, dogs, aardvarks, etc.) problem.
In this problem,
there are four bugs that begin on the vertices of a square with side length of r, say one meter.
They all begin to move towards
their clockwise neighbor with constant velocity, say 1 m/s, and we want to know how long
it will take before the bugs meet in the middle of the square (assuming the bugs are
insignificantly small compared to the size of the square).

![Bugs!](http://mostlypri.me/images/bugs_1.png "The Four Bugs Problem")

At first glance this can look like quite an intimidating problem, as the bugs are constantly
spiraling and changing directions. Before you break out the trigonometry and calculus, 
let's first ask ourselves if there is a simpler way of looking at these confounding insects.
If all of the bugs moved in a straight line towards the middle of the square, the problem
would be easy; it is the spiraling motion that makes this appear difficult.
How about we look at what happens when we as the observers rotate with the bugs?
This is a basic example of changing the frame of reference of a problem, and there is
nothing wrong with looking at the problem in this manner if we can convert all of the motion
into this new coordinate system. It turns out that since all of the bugs began in a
symmetric formation and they move in identical manners that maintain this symmetry, the
overall configuration of the four bugs will always be a square! It is a square because
the distances
between every bug and its pursuer will always be the same as the distances between the
other bugs and their pursuers, and the angles between bugs will likewise remain stable.
This is an example of finding invariants in a problem (another cool technique) but for
our purposes this is important because it means that, if we were to spin our frame of
reference along with the bugs, we would always observe the bugs in a square formation,
and each bug would move in a straight line towards the center! Now we need to figure
out how quickly the bugs will be moving. Finding this is a straightforward
application of trigonometry, as each bug will move towards its neighbor with speed 1 m/s,
and this makes a 45-degree angle with the path to the center of the square, so in our new
perspective, each bug moves 1 m/s * cos(45) = 1/&radic;2 m/s towards the center.

![Splat](http://mostlypri.me/images/bugs_2.png "Upon closer inspection...")

Now all we
need to do is figure out the distance to the center of the square, which is actually the same
calculation (just replace 1 m/s with 1 m), so the bugs will both catch and be caught by 
their neighbors in exactly 1 second!

The purpose of this example is to give a quick illustration of the immense difference
there is in solving
problems in different perspectives. Trying to figure out the motion of the spiraling
insects is doable, but much more unwieldy than dealing with the straightforward lines we
get after a frame of reference shift. Try it out for yourself! It is surprising how many
problems can be simplified by relatively painless operations.

Now that I have (hopefully) whet your appetite, next time we will
be diving more into reference frames and some relativity. I hope to see you there!

-Bryce
