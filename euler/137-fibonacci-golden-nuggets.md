Fibonacci golden nuggets
------------------------

*Source: https://projecteuler.net/problem=137*


*Difficulty rating: 50%*

Consider the infinite polynomial series A<sub>F</sub>(*x*) = *x*F<sub>1</sub> + *x*<sup>2</sup>F<sub>2</sub>
+ *x*<sup>3</sup>F<sub>3</sub> + ..., where F<sub>*k*</sub> is the *k*th term in the Fibonacci
sequence: 1, 1, 2, 3, 5, 8, ... ; that is, F<sub>*k*</sub> = F<sub>*k*−1</sub> + F<sub>*k*−2</sub>,
F<sub>1</sub> = 1 and F<sub>2</sub> = 1.

For this problem we shall be interested in values of *x* for which
A<sub>F</sub>(*x*) is a positive integer.

  ------------------------ ------------------------ ------------------------
  Surprisingly A<sub>F</sub>(1/2)                             
   =                        =                        = 
  (1/2).1 + (1/2)<sup>2</sup>.1 +   1/2 + 1/4 + 2/8 + 3/16 + 2
  (1/2)<sup>3</sup>.2 + (1/2)<sup>4</sup>.3  5/32 + ...               
  + (1/2)<sup>5</sup>.5 + ...                                
  ------------------------ ------------------------ ------------------------

The corresponding values of *x* for the first five natural numbers are
shown below.

  ------------------------------------ ------------------------------------
  ***x***                              √2−1
  **A<sub>F</sub>(*x*)**                        1
  ------------------------------------ ------------------------------------

We shall call A<sub>F</sub>(*x*) a golden nugget if *x* is rational, because they
become increasingly rarer; for example, the 10th golden nugget is
74049690.

Find the 15th golden nugget.
