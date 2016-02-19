Bounded Sequences
-----------------

*Source: https://projecteuler.net/problem=319*


*Difficulty rating: 90%*

Let x<sub>1</sub>, x<sub>2</sub>,..., x<sub>n</sub> be a sequence of length n such that:

-   x<sub>1</sub> = 2
-   for all 1 \< i ≤ n : x<sub>i-*1*</sub> \< x<sub>i</sub>
-   for all i and j with 1 ≤ i, j ≤ n : (x<sub>i</sub>) <sup>j</sup> \< (x<sub>j</sub> + 1)<sup>i</sup>

There are only five such sequences of length 2, namely: {2,4}, {2,5},
{2,6}, {2,7} and {2,8}.\
 There are 293 such sequences of length 5; three examples are given
below:\
 {2,5,11,25,55}, {2,6,14,36,88}, {2,8,22,64,181}.

Let t(n) denote the number of such sequences of length n.\
 You are given that t(10) = 86195 and t(20) = 5227991891.

Find t(10<sup>10</sup>) and give your answer modulo 10<sup>9</sup>.
