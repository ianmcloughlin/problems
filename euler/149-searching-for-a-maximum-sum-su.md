Searching for a maximum-sum subsequence
---------------------------------------

*Source: https://projecteuler.net/problem=149*


*Difficulty rating: 50%*

Looking at the table below, it is easy to verify that the maximum
possible sum of adjacent numbers in any direction (horizontal, vertical,
diagonal or anti-diagonal) is 16 (= 8 + 7 + 1).

  ------------------ ------------------ ------------------ ------------------
  −2                 9                  3                  −1
  5                  −6                 2                  8
  3                  5                  7                  −4
  2                  1                  3                    8
  ------------------ ------------------ ------------------ ------------------

Now, let us repeat the search, but on a much larger scale:

First, generate four million pseudo-random numbers using a specific form
of what is known as a "Lagged Fibonacci Generator":

For 1 ≤ *k* ≤ 55, *s*<sub>*k*</sub> = [100003 − 200003*k* + 300007*k*<sup>3</sup>] (modulo
1000000) − 500000.\
 For 56 ≤ *k* ≤ 4000000, *s*<sub>*k*</sub> = [*s*<sub>*k−24*</sub> + *s*<sub>*k−55*</sub> +
1000000] (modulo 1000000) − 500000.

Thus, *s*<sub>10</sub> = −393027 and *s*<sub>100</sub> = 86613.

The terms of *s* are then arranged in a 2000×2000 table, using the first
2000 numbers to fill the first row (sequentially), the next 2000 numbers
to fill the second row, and so on.

Finally, find the greatest sum of (any number of) adjacent entries in
any direction (horizontal, vertical, diagonal or anti-diagonal).
