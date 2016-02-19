Spilling the beans
------------------

*Source: https://projecteuler.net/problem=334*


*Difficulty rating: 65%*

In Plato's heaven, there exist an infinite number of bowls in a straight
line.\
 Each bowl either contains some or none of a finite number of beans.\
 A child plays a game, which allows only one kind of move: removing two
beans from any bowl, and putting one in each of the two adjacent bowls.\
 The game ends when each bowl contains either one or no beans.

For example, consider two adjacent bowls containing 2 and 3 beans
respectively, all other bowls being empty. The following eight moves
will finish the game:

![p334\_beans.gif](img/p334_beans.gif)

You are given the following sequences:\

  ------------------
  t~*0*~ = 123456.
  ------------------

t~*i*~ =

![p334\_cases.gif](img/p334_cases.gif)

  ---------- ---
  t~*i-1*~
  ---------- ---

,

if t~*i-1*~ is even

![p334\_lfloor.gif](img/p334_lfloor.gif)

  ---------- ---
  t~*i-1*~
  ---------- ---

![p334\_rfloor.gif](img/p334_rfloor.gif)

926252,

if t~*i-1*~ is odd

where ⌊x⌋ is the floor function

and ![p334\_oplus.gif](img/p334_oplus.gif) is the bitwise XOR
operator.

  -----------------------------------
  b~*i*~ = ( t~*i*~ mod 2<sup>11</sup>) + 1.
  -----------------------------------

The first two terms of the last sequence are b~*1*~ = 289 and b~*2*~ =
145.\
 If we start with b~*1*~ and b~*2*~ beans in two adjacent bowls, 3419100
moves would be required to finish the game.

Consider now 1500 adjacent bowls containing b~*1*~, b~*2*~,...,
b~*1500*~ beans respectively, all other bowls being empty. Find how many
moves it takes before the game ends.