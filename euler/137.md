Fibonacci golden nuggets
------------------------

*Source: https://projecteuler.net/problem=137*


*Difficulty rating: 50%*

Consider the infinite polynomial series A~F~(*x*) = *x*F~1~ + *x*<sup>2</sup>F~2~
+ *x*<sup>3</sup>F~3~ + ..., where F~*k*~ is the *k*th term in the Fibonacci
sequence: 1, 1, 2, 3, 5, 8, ... ; that is, F~*k*~ = F~*k*−1~ + F~*k*−2~,
F~1~ = 1 and F~2~ = 1.

For this problem we shall be interested in values of *x* for which
A~F~(*x*) is a positive integer.

  ------------------------ ------------------------ ------------------------
  Surprisingly A~F~(1/2)                             
   =                        =                        = 
  (1/2).1 + (1/2)<sup>2</sup>.1 +   1/2 + 1/4 + 2/8 + 3/16 + 2
  (1/2)<sup>3</sup>.2 + (1/2)<sup>4</sup>.3  5/32 + ...               
  + (1/2)<sup>5</sup>.5 + ...                                
  ------------------------ ------------------------ ------------------------

The corresponding values of *x* for the first five natural numbers are
shown below.

  ------------------------------------ ------------------------------------
  ***x***                              √2−1
  **A~F~(*x*)**                        1
  ------------------------------------ ------------------------------------

We shall call A~F~(*x*) a golden nugget if *x* is rational, because they
become increasingly rarer; for example, the 10th golden nugget is
74049690.

Find the 15th golden nugget.
