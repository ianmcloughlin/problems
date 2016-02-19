Integer-valued polynomials
--------------------------

*Source: https://projecteuler.net/problem=402*


*Difficulty rating: 55%*

It can be shown that the polynomial n<sup>4</sup> + 4n<sup>3</sup> + 2n<sup>2</sup> + 5n is a
multiple of 6 for every integer n. It can also be shown that 6 is the
largest integer satisfying this property.

Define M(a, b, c) as the maximum m such that n<sup>4</sup> + an<sup>3</sup> + bn<sup>2</sup> + cn
is a multiple of m for all integers n. For example, M(4, 2, 5) = 6.

Also, define S(N) as the sum of M(a, b, c) for all 0 \< a, b, c ≤ N.

We can verify that S(10) = 1972 and S(10000) = 2024258331114.

Let F~k~ be the Fibonacci sequence:\
 F~0~ = 0, F~1~ = 1 and\
 F~k~ = F~k-1~ + F~k-2~ for k ≥ 2.

Find the last 9 digits of Σ S(F~k~) for 2 ≤ k ≤ 1234567890123.
