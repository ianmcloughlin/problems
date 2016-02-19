Almost Pi
---------

*Source: https://projecteuler.net/problem=461*


*Difficulty rating: 30%*

Let f<sub>n</sub>(k) = e<sup>k/n</sup> - 1, for all non-negative integers k.

Remarkably, f<sub>200</sub>(6) + f<sub>200</sub>(75) + f<sub>200</sub>(89) + f<sub>200</sub>(226) =
3.141592644529… ≈ π.

In fact, it is the best approximation of π of the form
f<sub>n</sub>(a) + f<sub>n</sub>(b) + f<sub>n</sub>(c) + f<sub>n</sub>(d) for n = 200.

Let g(n) = a<sup>2</sup> + b<sup>2</sup> + c<sup>2</sup> + d<sup> 2</sup> for a, b, c, d that minimize the
error: | f<sub>n</sub>(a) + f<sub>n</sub>(b) + f<sub>n</sub>(c) + f<sub>n</sub>(d) - π|\
 (where |x| denotes the absolute value of x).

You are given g(200) = 6<sup>2</sup> + 75<sup>2</sup> + 89<sup>2</sup> + 226<sup>2</sup> = 64658.

Find g(10000).<sup></sup>
