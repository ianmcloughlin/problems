Roots on the Rise
-----------------

*Source: https://projecteuler.net/problem=479*


*Difficulty rating: 25%*

Let a<sub>k</sub>, b<sub>k</sub>, and c<sub>k</sub> represent the three solutions (real or complex
numbers) to the expression 1/x = (k/x)<sup>2</sup>(k+x<sup>2</sup>) - kx.

For instance, for k = 5, we see that {a<sub>5</sub>, b<sub>5</sub>, c<sub>5</sub>} is approximately
{5.727244, -0.363622+2.057397i, -0.363622-2.057397i}.

Let S(n) = Σ (a<sub>k</sub>+b<sub>k</sub>)<sup>p</sup>(b<sub>k</sub>+c<sub>k</sub>)<sup>p</sup>(c<sub>k</sub>+a<sub>k</sub>)<sup>p</sup> for all integers
p, k such that 1 ≤ p, k ≤ n.

Interestingly, S(n) is always an integer. For example, S(4) = 51160.

Find S(10<sup>6</sup>) modulo 1 000 000 007.
