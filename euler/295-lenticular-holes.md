Lenticular holes
----------------

*Source: https://projecteuler.net/problem=295*


*Difficulty rating: 75%*

We call the convex area enclosed by two circles a *lenticular hole* if:

-   The centres of both circles are on lattice points.
-   The two circles intersect at two distinct lattice points.
-   The interior of the convex area enclosed by both circles does not
    contain any lattice points.

Consider the circles:\
 C<sub>0</sub>: x<sup>2</sup>+y<sup>2</sup>=25\
 C<sub>1</sub>: (x+4)<sup>2</sup>+(y-4)<sup>2</sup>=1\
 C<sub>2</sub>: (x-12)<sup>2</sup>+(y-4)<sup>2</sup>=65

The circles C<sub>0</sub>, C<sub>1</sub> and C<sub>2</sub> are drawn in the picture below.

![p295\_lenticular.gif](img/p295_lenticular.gif)

C<sub>0</sub> and C<sub>1</sub> form a lenticular hole, as well as C<sub>0</sub> and C<sub>2</sub>.

We call an ordered pair of positive real numbers (r<sub>1</sub>, r<sub>2</sub>) a
*lenticular pair* if there exist two circles with radii r<sub>1</sub> and r<sub>2</sub>
that form a lenticular hole. We can verify that (1, 5) and (5, √65) are
the lenticular pairs of the example above.

Let L(N) be the number of **distinct** lenticular pairs (r<sub>1</sub>, r<sub>2</sub>) for
which 0 \< r<sub>1</sub> ≤ r<sub>2</sub> ≤ N.\
 We can verify that L(10) = 30 and L(100) = 3442.

Find L(100 000).
