Integers in base i-1
--------------------

*Source: https://projecteuler.net/problem=508*


*Difficulty rating: 85%*

Consider the Gaussian integer i-1. A **base i-1 representation** of a
Gaussian integer a+bi is a finite sequence of digits
d<sub>n-1</sub>d<sub>n-2</sub>...d<sub>1</sub>d<sub>0</sub> such that:

-   a+bi = d<sub>n-1</sub>(i-1)<sup>n-1</sup> + d<sub>n-2</sub>(i-1)<sup>n-2</sup> + ... + d<sub>1</sub>(i-1) + d<sub>0</sub>
-   Each d<sub>k</sub> is in {0,1}
-   There are no leading zeroes, i.e. d<sub>n-1</sub> ≠ 0, unless a+bi is itself
    0

Here are base i-1 representations of a few Gaussian integers:\
\
 11+24i → 111010110001101\
 24-11i → 110010110011\
 8+0i → 111000000\
 -5+0i → 11001101\
 0+0i → 0

Remarkably, every Gaussian integer has a unique base i-1
representation!\
\
 Define f(a+bi) as the number of 1s in the unique base i-1
representation of a+bi. For example, f(11+24i) = 9 and f(24-11i) = 7.\
\
 Define B(L) as the sum of f(a+bi) for all integers a, b such that |a| ≤
L and |b| ≤ L. For example, B(500) = 10795060.\
\
 Find B(10<sup>15</sup>) mod 1 000 000 007.
