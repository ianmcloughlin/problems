Combined Volume of Cuboids
--------------------------

*Source: https://projecteuler.net/problem=212*


*Difficulty rating: 70%*

An axis-aligned cuboid, specified by parameters { (x<sub>0</sub>,y<sub>0</sub>,z<sub>0</sub>),
(dx,dy,dz) }, consists of all points (X,Y,Z) such that x<sub>0</sub> ≤ X ≤
x<sub>0</sub>+dx, y<sub>0</sub> ≤ Y ≤ y<sub>0</sub>+dy and z<sub>0</sub> ≤ Z ≤ z<sub>0</sub>+dz. The volume of the
cuboid is the product, dx × dy × dz. The combined volume of a collection
of cuboids is the volume of their union and will be less than the sum of
the individual volumes if any cuboids overlap.

Let C<sub>1</sub>,...,C<sub>50000</sub> be a collection of 50000 axis-aligned cuboids such
that C<sub>n</sub> has parameters

x<sub>0</sub> = S<sub>6n-5</sub> modulo 10000\
y<sub>0</sub> = S<sub>6n-4</sub> modulo 10000\
z<sub>0</sub> = S<sub>6n-3</sub> modulo 10000\
dx = 1 + (S<sub>6n-2</sub> modulo 399)\
dy = 1 + (S<sub>6n-1</sub> modulo 399)\
dz = 1 + (S<sub>6n</sub> modulo 399)

where S<sub>1</sub>,...,S<sub>300000</sub> come from the "Lagged Fibonacci Generator":

For 1 ≤ k ≤ 55, S<sub>k</sub> = [100003 - 200003k + 300007k<sup>3</sup>]   (modulo
1000000)\
For 56 ≤ k, S<sub>k</sub> = [S<sub>k-24</sub> + S<sub>k-55</sub>]   (modulo 1000000)

Thus, C<sub>1</sub> has parameters {(7,53,183),(94,369,56)}, C<sub>2</sub> has parameters
{(2383,3563,5079),(42,212,344)}, and so on.

The combined volume of the first 100 cuboids, C<sub>1</sub>,...,C<sub>100</sub>, is
723581599.

What is the combined volume of all 50000 cuboids, C<sub>1</sub>,...,C<sub>50000</sub> ?
