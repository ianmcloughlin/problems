Remainder of polynomial division
--------------------------------

*Source: https://projecteuler.net/problem=498*


*Difficulty rating: 40%*

For positive integers n and m, we define two polynomials F<sub>n</sub>(x) = x<sup>n</sup>
and G<sub>m</sub>(x) = (x-1)<sup>m</sup>.\
 We also define a polynomial R<sub>n,m</sub>(x) as the remainder of the division
of F<sub>n</sub>(x) by G<sub>m</sub>(x).\
 For example, R<sub>6,3</sub>(x) = 15x<sup>2</sup> - 24x + 10.

Let C(n, m, d) be the absolute value of the coefficient of the d-th
degree term of R<sub>n,m</sub>(x).\
 We can verify that C(6, 3, 1) = 24 and C(100, 10, 4) = 227197811615775.

Find C(10<sup>13</sup>, 10<sup>12</sup>, 10<sup>4</sup>) mod 999999937.
