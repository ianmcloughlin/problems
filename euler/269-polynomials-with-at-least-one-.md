Polynomials with at least one integer root
------------------------------------------

*Source: https://projecteuler.net/problem=269*


*Difficulty rating: 80%*

A root or zero of a polynomial P(x) is a solution to the equation P(x) =
0.\
 Define P<sub>n</sub> as the polynomial whose coefficients are the digits of n.\
 For example, P<sub>5703</sub>(x) = 5x<sup>3</sup> + 7x<sup>2</sup> + 3.

We can see that:

-   P<sub>n</sub>(0) is the last digit of n,
-   P<sub>n</sub>(1) is the sum of the digits of n,
-   P<sub>n</sub>(10) is n itself.

Define Z(k) as the number of positive integers, n, not exceeding k for
which the polynomial P<sub>n</sub> has at least one integer root.

It can be verified that Z(100 000) is 14696.

What is Z(10<sup>16</sup>)?
