Robots were returning to energy base in small groups or by themselves and did not see each other upon their return,
so each group did not know how many robots had fueled their part of the squad energy container.
Some groups know about how big the container was,
but other groups don't know this and think the remaining part is the whole energy, then take their portion from the remaining.
So each group had divided (mentally) the remaining or initial volume at all and took their part.
How many parts will remain after all of the robots return?

Let’s take a look at an example of how this should work:
There are 6 robots. The first group consists of 2 robots.
They had divided the energy into 6 parts and took 2/6 of it.
The remainder of the energy is 2/3 of the initial volume.
Next returns a single robot, it doesn’t know about the original size of the pie,
so it divides the remaining energy into 6 parts and takes 1 part.
This leaves `10/18 = 5/9` . The last group is 3 robots,
which heard about the original volume.
They took half of the original container, so the remaining is `5/9 - 3/6 = 1/18`

You are given an ordered array with sizes of the groups in the order they arrived.
If a group knows about the initial container volume, then the size is positive.
If not, then size will be negative. The recent example will given as (2, -1, 3).

![Pie](oil-pie.png)

You should calculate the size as remaining energy in container as a fraction from the start size.
The result should be represented as two numbers - numerator and denominator.
Zero should be represented as (0, 1).
