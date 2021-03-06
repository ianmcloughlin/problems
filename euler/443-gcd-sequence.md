GCD sequence
------------

*Source: https://projecteuler.net/problem=443*


*Difficulty rating: 30%*

Let g(n) be a sequence defined as follows:\
 g(4) = 13,\
 g(n) = g(n-1) + gcd(n, g(n-1)) for n \> 4.

The first few values are:

  --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
  n   g(n
  4   )
  5   13
  6   14
  7   16
  8   17
  9   18
  10  27
  11  28
  12  29
  13  30
  14  31
  15  32
  16  33
  17  34
  18  51
  19  54
  20  55
  ... 60
      ...
  --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---

You are given that g(1 000) = 2524 and g(1 000 000) = 2624152.

Find g(10<sup>15</sup>).
