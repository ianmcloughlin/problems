Minkowski Sums
--------------

*Source: https://projecteuler.net/problem=228*


*Difficulty rating: 70%*

Let S~n~ be the regular n-sided polygon – or *shape* – whose vertices
v~k~ (k = 1,2,…,n) have coordinates:

  ------------------------------------ ------------------------------------
  x~k~   =   cos( <sup>2k-1</sup>/~n~ ×180° )
  ------------------------------------ ------------------------------------

Each S~n~ is to be interpreted as a filled shape consisting of all
points on the perimeter and in the interior.

The *Minkowski sum*, S+T, of two shapes S and T is the result of adding
every point in S to every point in T, where point addition is performed
coordinate-wise: (u, v) + (x, y) = (u+x, v+y).

For example, the sum of S~3~ and S~4~ is the six-sided shape shown in
pink below:

![picture showing S\_3 + S\_4](img/p228.png)

How many sides does S~1864~ + S~1865~ + … + S~1909~ have?