Convex Holes
------------

*Source: https://projecteuler.net/problem=252*


*Difficulty rating: 80%*

Given a set of points on a plane, we define a convex hole to be a convex
polygon having as vertices any of the given points and not containing
any of the given points in its interior (in addition to the vertices,
other given points may lie on the perimeter of the polygon).

As an example, the image below shows a set of twenty points and a few
such convex holes. The convex hole shown as a red heptagon has an area
equal to 1049694.5 square units, which is the highest possible area for
a convex hole on the given set of points.

![](img/p252_convexhole.gif)

For our example, we used the first 20 points (T<sub>2k−1</sub>, T<sub>2k</sub>), for
k = 1,2,…,20, produced with the pseudo-random number generator:

  ------------------------ ------------------------ ------------------------
  S<sub>0</sub>                     S<sub>n+1</sub>                   T<sub>n</sub>
  =<sub> </sub>                     =<sub> </sub>                     =<sub> </sub>
  290797<sub> </sub>                S<sub>n</sub><sup>2</sup> mod 50515093     ( S<sub>n</sub> mod 2000 ) −
                                                    1000<sup> </sup>
  ------------------------ ------------------------ ------------------------

*i.e.* (527, 144), (−488, 732), (−454, −947), …

What is the maximum area for a convex hole on the set containing the
first 500 points in the pseudo-random sequence?\
 Specify your answer including one digit after the decimal point.
