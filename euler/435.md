Polynomials of Fibonacci numbers
--------------------------------

*Source: https://projecteuler.net/problem=435*


*Difficulty rating: 30%*

The **Fibonacci numbers** {f~n~, n ≥ 0} are defined recursively as f~n~
= f~n-1~ + f~n-2~ with base cases f~0~ = 0 and f~1~ = 1.

Define the polynomials {F~n~, n ≥ 0} as F~n~(x) = ∑f~i~x<sup>i</sup> for 0 ≤ i ≤
n.

For example, F~7~(x) = x + x<sup>2</sup> + 2x<sup>3</sup> + 3x<sup>4</sup> + 5x<sup>5</sup> + 8x<sup>6</sup> +
13x<sup>7</sup>, and F~7~(11) = 268357683.

Let n = 10<sup>15</sup>. Find the sum [∑~0≤x≤100~ F~n~(x)] mod 1307674368000 (=
15!).
