Numbers in decimal expansions
-----------------------------

*Source: https://projecteuler.net/problem=316*


*Difficulty rating: 55%*

Let p = p<sub>1</sub> p<sub>2</sub> p<sub>3</sub> ... be an infinite sequence of random digits,
selected from {0,1,2,3,4,5,6,7,8,9} with equal probability.\
 It can be seen that p corresponds to the real number 0.p<sub>1</sub> p<sub>2</sub> p<sub>3</sub>
....\
 It can also be seen that choosing a random real number from the
interval [0,1) is equivalent to choosing an infinite sequence of random
digits selected from {0,1,2,3,4,5,6,7,8,9} with equal probability.

For any positive integer n with d decimal digits, let k be the smallest
index such that\
p<sub>k,</sub> p<sub>k+1</sub>, ...p<sub>k+d-1</sub> are the decimal digits of n, in the same
order.\
 Also, let g(n) be the expected value of k; it can be proven that g(n)
is always finite and, interestingly, always an integer number.

For example, if n = 535, then\
 for p = 31415926**535**897...., we get k = 9\
 for p = 35528714365004956000049084876408468**535**4..., we get k = 36\
 etc and we find that g(535) = 1008.

Given that ![p316\_decexp1.gif](img/p316_decexp1.gif), find
![p316\_decexp2.gif](img/p316_decexp2.gif)

*Note*: ![p316\_decexp3.gif](img/p316_decexp3.gif) represents
the floor function.
