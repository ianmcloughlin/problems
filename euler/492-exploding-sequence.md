Exploding sequence
------------------

*Source: https://projecteuler.net/problem=492*


*Difficulty rating: 60%*

Define the sequence a<sub>1</sub>, a<sub>2</sub>, a<sub>3</sub>, ... as:

-   a<sub>1</sub> = 1
-   a<sub>n+1</sub> = 6a<sub>n</sub><sup>2</sup> + 10a<sub>n</sub> + 3 for n ≥ 1.

Examples:\
 a<sub>3</sub> = 2359\
 a<sub>6</sub> = 269221280981320216750489044576319\
 a<sub>6</sub> mod 1 000 000 007 = 203064689\
 a<sub>100</sub> mod 1 000 000 007 = 456482974

Define B(x,y,n) as ∑ (a<sub>n</sub> mod p) for every prime p such that x ≤ p ≤
x+y.

Examples:\
 B(10<sup>9</sup>, 10<sup>3</sup>, 10<sup>3</sup>) = 23674718882\
 B(10<sup>9</sup>, 10<sup>3</sup>, 10<sup>15</sup>) = 20731563854

Find B(10<sup>9</sup>, 10<sup>7</sup>, 10<sup>15</sup>).
