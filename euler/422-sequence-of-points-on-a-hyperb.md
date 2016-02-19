Sequence of points on a hyperbola
---------------------------------

*Source: https://projecteuler.net/problem=422*

Published on Sunday, 7th April 2013, 07:00 am; Solved by 167; Difficulty
rating: 75%

Let H be the hyperbola defined by the equation 12x<sup>2</sup> + 7xy - 12y<sup>2</sup> =
625.

Next, define X as the point (7, 1). It can be seen that X is in H.

Now we define a sequence of points in H, {P<sub>i</sub> : i ≥ 1}, as:

-   P<sub>1</sub> = (13, 61/4).
-   P<sub>2</sub> = (-43/6, -4).
-   For i \> 2, P<sub>i</sub> is the unique point in H that is different from
    P<sub>i-1</sub> and such that line P<sub>i</sub>P<sub>i-1</sub> is parallel to line P<sub>i-2</sub>X. It
    can be shown that P<sub>i</sub> is well-defined, and that its coordinates are
    always rational.

![p422\_hyperbola.gif](img/p422_hyperbola.gif)

You are given that P<sub>3</sub> = (-19/2, -229/24), P<sub>4</sub> = (1267/144, -37/12)
and P<sub>7</sub> = (17194218091/143327232, 274748766781/1719926784).

Find P<sub>n</sub> for n = 11<sup>14</sup> in the following format:\
If P<sub>n</sub> = (a/b, c/d) where the fractions are in lowest terms and the
denominators are positive, then the answer is (a + b + c + d) mod
1 000 000 007.

For n = 7, the answer would have been: 806236837.
