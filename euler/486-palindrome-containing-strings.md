Palindrome-containing strings
-----------------------------

*Source: https://projecteuler.net/problem=486*


*Difficulty rating: 70%*

Let F<sub>5</sub>(n) be the number of strings s such that:

-   s consists only of '0's and '1's,
-   s has length at most n, and
-   s contains a palindromic substring of length at least 5.

For example, F<sub>5</sub>(4) = 0, F<sub>5</sub>(5) = 8, F<sub>5</sub>(6) = 42 and F<sub>5</sub>(11) = 3844.

Let D(L) be the number of integers n such that 5 ≤ n ≤ L and F<sub>5</sub>(n) is
divisible by 87654321.

For example, D(10<sup>7</sup>) = 0 and D(5·10<sup>9</sup>) = 51.

Find D(10<sup>18</sup>).
