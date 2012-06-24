The Rabbit Question
===================

I was asked this question a long time ago at one of my first interviews out of college and it has stuck with me
ever since. I personally think it's a great question because it gives you an opportunity, as an interviewer, to 
see how the candidate thinks and also opens up many avenues of discussion.

First, the setup
----------------

There is a rabbit (or other hopping animal you can draw) at the bottom of a set of stairs. The rabbit can hop up 
one step at a time to reach the top, or he can hop up two steps at a time. How many different combinations of hops 
are there for n steps. Write an algorithm to calculate the number of hop combinations for n steps. 

Example - 4 steps

1-1-1-1 = 4
2-1-1   = 4
1-2-1   = 4
1-1-2   = 4
2-2     = 4

So for 4 steps, there are 5 possible different combinations of 1-2 hops to reach the top.

The answer
----------

If you work out the number of possible hops for the first few steps you end up with:

n | hops
--------
1 | 1
2 | 2
3 | 3
4 | 5
5 | 8
6 | 13

This is the fibonacci sequence (the next number in the sequence is the sum of the two previous numbers).