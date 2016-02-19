Minimum of subsequences
-----------------------

*Source: https://projecteuler.net/problem=375*


*Difficulty rating: 40%*

Let S<sub>n</sub> be an integer sequence produced with the following
pseudo-random number generator:

  ------------------------ ------------------------ ------------------------
  S<sub>0</sub>                     S<sub>n+1</sub>
  =<sub> </sub>                     =<sub> </sub>
  290797<sub> </sub>                S<sub>n</sub><sup>2</sup> mod 50515093
  ------------------------ ------------------------ ------------------------

Let A(i, j) be the minimum of the numbers S<sub>i</sub>, S<sub>i+1</sub>, ... , S<sub>j</sub> for i
≤ j.\
 Let M(N) = ΣA(i, j) for 1 ≤ i ≤ j ≤ N.\
 We can verify that M(10) = 432256955 and M(10 000) = 3264567774119.

Find M(2 000 000 000).
