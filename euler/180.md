Rational zeros of a function of three variables
-----------------------------------------------

*Source: https://projecteuler.net/problem=180*


*Difficulty rating: 75%*

For any integer n, consider the three functions

f~1,n~(x,y,z) = x<sup>n+1</sup> + y<sup>n+1</sup> − z<sup>n+1</sup>\
f~2,n~(x,y,z) = (xy + yz + zx)\*(x<sup>n-1</sup> + y<sup>n-1</sup> − z<sup>n-1</sup>)\
f~3,n~(x,y,z) = xyz\*(x<sup>n-2</sup> + y<sup>n-2</sup> − z<sup>n-2</sup>)

and their combination

f~n~(x,y,z) = f~1,n~(x,y,z) + f~2,n~(x,y,z) − f~3,n~(x,y,z)

We call (x,y,z) a golden triple of order k if x, y, and z are all
rational numbers of the form a / b with\
 0 \< a \< b ≤ k and there is (at least) one integer n, so that
f~n~(x,y,z) = 0.

Let s(x,y,z) = x + y + z.\
 Let t = u / v be the sum of all distinct s(x,y,z) for all golden
triples (x,y,z) of order 35.\
 All the s(x,y,z) and t must be in reduced form.

Find u + v.
