Common factors between two sequences
------------------------------------

*Source: https://projecteuler.net/problem=489*


*Difficulty rating: 100%*

Let G(a, b) be the smallest non-negative integer n for which gcd(n<sup>3</sup> +
b, (n + a)<sup>3</sup> + b) is maximized.\
 For example, G(1, 1) = 5 because gcd(n<sup>3</sup> + 1, (n + 1)<sup>3</sup> + 1) reaches
its maximum value of 7 for n = 5, and is smaller for 0 ≤ n \< 5.\
 Let H(m, n) = Σ G(a, b) for 1 ≤ a ≤ m, 1 ≤ b ≤ n.\
 You are given H(5, 5) = 128878 and H(10, 10) = 32936544.

Find H(18, 1900).
