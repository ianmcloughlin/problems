Minkowski Sums
--------------

*Source: https://projecteuler.net/problem=228*


*Difficulty rating: 70%*

Let S<sub>n</sub> be the regular n-sided polygon – or *shape* – whose vertices
v<sub>k</sub> (k = 1,2,…,n) have coordinates:

  ------------------------------------ ------------------------------------
  x<sub>k</sub>   =   cos( <sup>2k-1</sup>/<sub>n</sub> ×180° )
  ------------------------------------ ------------------------------------

Each S<sub>n</sub> is to be interpreted as a filled shape consisting of all
points on the perimeter and in the interior.

The *Minkowski sum*, S+T, of two shapes S and T is the result of adding
every point in S to every point in T, where point addition is performed
coordinate-wise: (u, v) + (x, y) = (u+x, v+y).

For example, the sum of S<sub>3</sub> and S<sub>4</sub> is the six-sided shape shown in
pink below:

![picture showing S\_3 + S\_4](img/p228.png)

How many sides does S<sub>1864</sub> + S<sub>1865</sub> + … + S<sub>1909</sub> have?
