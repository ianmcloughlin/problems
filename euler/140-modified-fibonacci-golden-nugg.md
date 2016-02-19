Modified Fibonacci golden nuggets
---------------------------------

*Source: https://projecteuler.net/problem=140*


*Difficulty rating: 55%*

Consider the infinite polynomial series A<sub>G</sub>(*x*) = *x*G<sub>1</sub> + *x*<sup>2</sup>G<sub>2</sub>
+ *x*<sup>3</sup>G<sub>3</sub> + ..., where G<sub>*k*</sub> is the *k*th term of the second order
recurrence relation G<sub>*k*</sub> = G<sub>*k*−1</sub> + G<sub>*k*−2</sub>, G<sub>1</sub> = 1 and G<sub>2</sub> = 4;
that is, 1, 4, 5, 9, 14, 23, ... .

For this problem we shall be concerned with values of *x* for which
A<sub>G</sub>(*x*) is a positive integer.

The corresponding values of *x* for the first five natural numbers are
shown below.

  ------------------------------------ ------------------------------------
  ***x***                              (√5−1)/4
  **A<sub>G</sub>(*x*)**                        1
  ------------------------------------ ------------------------------------

We shall call A<sub>G</sub>(*x*) a golden nugget if *x* is rational, because they
become increasingly rarer; for example, the 20th golden nugget is
211345365.

Find the sum of the first thirty golden nuggets.
