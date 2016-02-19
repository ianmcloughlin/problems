Exploding sequence
------------------

*Source: https://projecteuler.net/problem=492*


*Difficulty rating: 60%*

Define the sequence a~1~, a~2~, a~3~, ... as:

-   a~1~ = 1
-   a~n+1~ = 6a~n~<sup>2</sup> + 10a~n~ + 3 for n ≥ 1.

Examples:\
 a~3~ = 2359\
 a~6~ = 269221280981320216750489044576319\
 a~6~ mod 1 000 000 007 = 203064689\
 a~100~ mod 1 000 000 007 = 456482974

Define B(x,y,n) as ∑ (a~n~ mod p) for every prime p such that x ≤ p ≤
x+y.

Examples:\
 B(10<sup>9</sup>, 10<sup>3</sup>, 10<sup>3</sup>) = 23674718882\
 B(10<sup>9</sup>, 10<sup>3</sup>, 10<sup>15</sup>) = 20731563854

Find B(10<sup>9</sup>, 10<sup>7</sup>, 10<sup>15</sup>).
