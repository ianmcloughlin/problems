Polynomials of Fibonacci numbers
--------------------------------

*Source: https://projecteuler.net/problem=435*


*Difficulty rating: 30%*

The **Fibonacci numbers** {f<sub>n</sub>, n ≥ 0} are defined recursively as f<sub>n</sub>
= f<sub>n-1</sub> + f<sub>n-2</sub> with base cases f<sub>0</sub> = 0 and f<sub>1</sub> = 1.

Define the polynomials {F<sub>n</sub>, n ≥ 0} as F<sub>n</sub>(x) = ∑f<sub>i</sub>x<sup>i</sup> for 0 ≤ i ≤
n.

For example, F<sub>7</sub>(x) = x + x<sup>2</sup> + 2x<sup>3</sup> + 3x<sup>4</sup> + 5x<sup>5</sup> + 8x<sup>6</sup> +
13x<sup>7</sup>, and F<sub>7</sub>(11) = 268357683.

Let n = 10<sup>15</sup>. Find the sum [∑<sub>0≤x≤100</sub> F<sub>n</sub>(x)] mod 1307674368000 (=
15!).
