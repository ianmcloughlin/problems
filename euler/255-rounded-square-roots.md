Rounded Square Roots
--------------------

*Source: https://projecteuler.net/problem=255*


*Difficulty rating: 75%*

We define the *rounded-square-root* of a positive integer n as the
square root of n rounded to the nearest integer.

The following procedure (essentially Heron's method adapted to integer
arithmetic) finds the rounded-square-root of n:

Let d be the number of digits of the number n.\
 If d is odd, set x<sub>0</sub> = 2×10<sup>(d-1)⁄2</sup>.\
 If d is even, set x<sub>0</sub> = 7×10<sup>(d-2)⁄2</sup>.\
 Repeat:

![p255\_Heron.gif](img/p255_Heron.gif)

until x<sub>k+1</sub> = x<sub>k</sub>.

As an example, let us find the rounded-square-root of n = 4321.\
n has 4 digits, so x<sub>0</sub> = 7×10<sup>(4-2)⁄2</sup> = 70.\
![p255\_Example.gif](img/p255_Example.gif)\
 Since x<sub>2</sub> = x<sub>1</sub>, we stop here.\
 So, after just two iterations, we have found that the
rounded-square-root of 4321 is 66 (the actual square root is
65.7343137…).

The number of iterations required when using this method is surprisingly
low.\
 For example, we can find the rounded-square-root of a 5-digit integer
(10,000 ≤ n ≤ 99,999) with an average of 3.2102888889 iterations (the
average value was rounded to 10 decimal places).

Using the procedure described above, what is the average number of
iterations required to find the rounded-square-root of a 14-digit number
(10<sup>13</sup> ≤ n \< 10<sup>14</sup>)?\
 Give your answer rounded to 10 decimal places.

Note: The symbols ⌊x⌋ and ⌈x⌉ represent the floor function and ceiling
function respectively.
