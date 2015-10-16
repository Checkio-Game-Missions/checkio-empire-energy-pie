The robots were returning to the energy charging base in small groups or by themselves and did not see each other upon their return. This meant that each group did not know how many robots had fueled their part of the squad energy container.
Some groups knew what the charged capacity of the battery was,
but other groups didn't know this information and think the remaining juice is the full capacity of the battery, then take their portion from the remaining electricity.
So, each group had divided the remaining or initial charge and took their part.
How much power will remain after all of the robots return from their mission?

Let’s take a look at an example of how this should work:
There are 6 robots. The first group consists of 2 robots.
They had divided the energy into 6 parts and took 2/6 of it.
The remainder of the energy is 2/3 of the initial charge.
Next returns a single robot, it doesn’t know about the original charge of the battery, so it divides the remaining energy into 6 parts and takes 1 part.
This leaves `10/18 = 5/9`. The last group is 3 robots, which knew about the original charge.
They took half of the original container, so the remaining is `5/9 - 3/6 = 1/18`

You are given an ordered array with sizes of the groups in the order they arrived.
If a group knows about the initial charge capacity, then the charge is positive.
If not, then charge will be negative. The recent example will given as (2, -1, 3).

```
######   ******   ......   ...... 
######   ******   ......   ......
######   ######   ****##   ....**
######   ######   ######   ****** 
######   ######   ######   ******
######   ######   ######   ****##
 init      2        -1       3
```

You should calculate the amount as remaining energy in the container as a fraction from the starting size.
The result should be represented as two numbers - numerator and denominator.
Zero should be represented as (0, 1).
