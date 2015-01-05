---
layout: post
title: "Avoiding the Drift to Low Performance"
tags: ["Community"]
author: "Paul Pagel"
tagline: "In various enchanted attitudes, like the standing, or stepping, or running skeletons in Herculaneum, others remained rooted to the deck; but all their eyes upcast."
category: featured
---

Estimates are a fundamental part of our business. We rely on them to schedule our workflow
and to communicate honestly and openly with clients. We need them in order to set deadlines
and goals for large projects. But estimates are human-made, fact-based fictions that we tell
ourselves in an attempt to understand the future, and there is no universally agreed-upon
method for formulating these estimates.

Typically, product owners want estimates to be absolutes that fit into concrete deadlines.
They want guarantees that remove the uncertainty from the future, because that’s what their
money is going toward. But when dealing with projects of larger scope, that’s an unrealistic
ideal. We can’t know how much effort a problem will require or the scope of the solution up
front.

<img src="/paul-pagel/images/2014-07-22-avoiding-the-drift-to-low-performance/01.png">

Even so, we do our best to meet this demand by using our own experience. You’re probably
familiar with the old axiom: past performance is the best predictor of future performance.
It’s the basis behind Mike Cohn’s estimating technique in the extremely popular book Agile
Estimation and Planning, in which he lays out the method of using historical values to predict
a team’s velocity on a project.

This is a relative estimation technique, and craftsmen are generally good at it. Our brains
can look at a problem and its component parts and compare them to other problems we’ve solved
in the past.

<img src="/paul-pagel/images/2014-07-22-avoiding-the-drift-to-low-performance/02.png">

While I don’t wholly disagree with Cohn’s ideas, my experience in software has not aligned
perfectly with this idea. Even relative estimation is an imperfect science that is vulnerable
to human error. We are prone to biases that affect our perceptions of how much work we completed,
how much time it will take to finish work in the future, and how one piece of a project compares
to another. Without checks in place, these variances can play off each other to create a system
trap.

What I’ve experienced is more in line with what Donella Meadows defines in her book Thinking In
Systems as the “drift to low performance.” She explains that “allowing performance standards to
be influenced by past performance, especially if there is a negative bias in perceiving past
performance, sets up a reinforcing feedback loop of eroding goals that sets a system drifting
toward low performance.”

As an example, Meadows cites the “boiled frog syndrome.” The old story goes that if you dump a
frog in boiling water, it will feel the scalding temperature and jump out immediately. But if you
put a frog in lukewarm water and slowly increase the temperature, it won’t notice the scalding
temperature. It gets warmer and warmer, but never so much warmer than it was a moment prior to
cause alarm in the frog. Eventually the frog gets boiled, and it has no idea.

Likewise, while our brains might be efficient at matching levels of complexity from one project
to the next, they’re not as good at defining how that complexity translates to a fixed or
absolute value.

Just about every project I’ve worked on begins the same way. We move at a consistent velocity,
smooth-sailing through lukewarm water. Sometimes we are a few points up, sometimes a few points
down, but we usually rebound the next week. Then we encounter the first event that is completely
unpredictable&mdash;a mini [Black Swan](http://en.wikipedia.org/wiki/Black_swan_theory) in
dependency, complexity, or distraction. Due to this, our story is only 90 percent done. We go in
to the next iteration with a little lower velocity and a little debt to this story. Most likely,
we’ll finish and everything will go back to normal, right?

Unfortunately, that’s not usually the case. A task that was difficult to estimate once because of
hidden complexity usually continues to be difficult. You ask for help, which causes difficulty
for others, too. Pretty soon, using last week’s velocity to set expectations has the whole team
completing fewer points, and working twice as hard to dig out of this “expectations gap.” In an
attempt to meet a fixed deadline, the amount of effort and time in each week becomes relative as
well. We work longer hours, and our work suffers. This becomes a negative feedback loop, and over
time creates a clear drift to low performance.

When we base our estimates entirely on relative measures, our standards fluctuate with our
performance every week. Meadows suggests a fairly simple way to avoid this trap, though: “Keep
performance standards absolute.”

At 8th Light, we have done this by making one point equal approximately four hours worth of work.
The size of this unit allows us to focus our estimates on the smallest, most predictable pieces of
a problem, while staying fixed to a standardized and predictable amount of time.

If we treat this absolute measure as one point on a spectrum, the opposite point is the relative
measure. The empty space between these two represents our “expectations gap.” It’s the distance
between what we perceive a problem to require, and what it actually requires.

<img src="/paul-pagel/images/2014-07-22-avoiding-the-drift-to-low-performance/03.png" style="border: none">

Every estimate we make lands somewhere along this spectrum, but this still allows for a fair
amount of uncertainty. We shrink that uncertainty by employing the PERT estimation method. With
PERT, each craftsman submits three estimates: an optimistic estimate, reflecting the amount of
effort required by an ideal and flawless solution; a realistic estimate, reflecting the amount of
effort the craftsman’s experience has led him or her to expect; and a pessimistic estimate,
reflecting the amount of effort required if absolutely everything went wrong.

PERT then applies an algorithm to these three figures to create a weighted realistic estimate.
This new estimate accounts for biases in both complexity and time, shortening the distance
between the two and making our estimates more precise.

<img src="/paul-pagel/images/2014-07-22-avoiding-the-drift-to-low-performance/04.png" style="border: none">

By affixing our estimates to a working week made of absolute units of time, we force ourselves to
jump into the pot of water each week. We don’t sit around all week trying to decide how our
temperature sits along a relative scale—we jump in and out and take a realistic measure of the
water’s actual temperature.

If we fall short of our estimation one week, we jump into the pot of water at our Iteration
Planning Meeting and we feel the heat. If we try to compensate for our estimates and begin to fall
into the feedback loop of eroding expectations, the water boils us immediately. There is no slow
erosion of expectations, because everything is judged against an absolute scale.

This has proven to be an extremely stable estimation method for us. We are forced to set a
sustainable pace, and have checks in place to protect us from our biases. There is no good news or
bad news—there is only news.
