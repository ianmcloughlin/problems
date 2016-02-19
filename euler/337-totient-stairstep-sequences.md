Totient Stairstep Sequences
---------------------------

*Source: https://projecteuler.net/problem=337*

Published on Saturday, 7th May 2011, 10:00 pm; Solved by 332; Difficulty
rating: 70%

Let {a<sub>1</sub>, a<sub>2</sub>,..., a<sub>n</sub>} be an integer sequence of length n such that:

-   a<sub>1</sub> = 6
-   for all 1 ≤ i \< n : φ(a<sub>i</sub>) \< φ(a<sub>i+1</sub>) \< a<sub>i</sub> \< a<sub>i+1</sub><sup>1</sup>

Let S(N) be the number of such sequences with a<sub>n</sub> ≤ N.\
 For example, S(10) = 4: {6}, {6, 8}, {6, 8, 9} and {6, 10}.\
 We can verify that S(100) = 482073668 and S(10 000) mod 10<sup>8</sup> =
73808307.

Find S(20 000 000) mod 10<sup>8</sup>.

<sup>1</sup> φ denotes **Euler's totient function**.
