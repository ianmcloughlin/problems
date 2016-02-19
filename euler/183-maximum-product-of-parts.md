Maximum product of parts
------------------------

*Source: https://projecteuler.net/problem=183*


*Difficulty rating: 45%*

Let N be a positive integer and let N be split into k equal parts, r =
N/k, so that N = r + r + ... + r.\
 Let P be the product of these parts, P = r × r × ... × r = r<sup>k</sup>.

For example, if 11 is split into five equal parts, 11 = 2.2 + 2.2 + 2.2
+ 2.2 + 2.2, then P = 2.2<sup>5</sup> = 51.53632.

Let M(N) = P<sub>max</sub> for a given value of N.

It turns out that the maximum for N = 11 is found by splitting eleven
into four equal parts which leads to P<sub>max</sub> = (11/4)<sup>4</sup>; that is, M(11)
= 14641/256 = 57.19140625, which is a terminating decimal.

However, for N = 8 the maximum is achieved by splitting it into three
equal parts, so M(8) = 512/27, which is a non-terminating decimal.

Let D(N) = N if M(N) is a non-terminating decimal and D(N) = -N if M(N)
is a terminating decimal.

For example, ΣD(N) for 5 ≤ N ≤ 100 is 2438.

Find ΣD(N) for 5 ≤ N ≤ 10000.
