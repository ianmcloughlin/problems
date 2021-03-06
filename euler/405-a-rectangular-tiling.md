A rectangular tiling
--------------------

*Source: https://projecteuler.net/problem=405*


*Difficulty rating: 40%*

We wish to tile a rectangle whose length is twice its width.\
 Let T(0) be the tiling consisting of a single rectangle.\
 For n \> 0, let T(n) be obtained from T(n-1) by replacing all tiles in
the following manner:

![p405\_tile1.png](img/p405_tile1.png)

The following animation demonstrates the tilings T(n) for n from 0 to 5:

![p405\_tile2.gif](img/p405_tile2.gif)

Let f(n) be the number of points where four tiles meet in T(n).\
 For example, f(1) = 0, f(4) = 82 and f(10<sup>9</sup>) mod 17<sup>7</sup> = 126897180.

Find f(10<sup>k</sup>) for k = 10<sup>18</sup>, give your answer modulo 17<sup>7</sup>.
