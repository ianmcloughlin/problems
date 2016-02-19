Cyclic paths on Sierpiński graphs
---------------------------------

*Source: https://projecteuler.net/problem=312*


*Difficulty rating: 50%*

- A **Sierpiński graph** of order-1 (S<sub>1</sub>) is an equilateral triangle.\
 - S<sub>n+1</sub> is obtained from S<sub>n</sub> by positioning three copies of S<sub>n</sub> so
that every pair of copies has one common corner.

![p312\_sierpinskyAt.gif](img/p312_sierpinskyAt.gif)

Let C(n) be the number of cycles that pass exactly once through all the
vertices of S<sub>n</sub>.\
 For example, C(3) = 8 because eight such cycles can be drawn on S<sub>3</sub>,
as shown below:

![p312\_sierpinsky8t.gif](img/p312_sierpinsky8t.gif)

It can also be verified that :\
 C(1) = C(2) = 1\
 C(5) = 71328803586048\
 C(10 000) mod 10<sup>8</sup> = 37652224\
 C(10 000) mod 13<sup>8</sup> = 617720485\

Find C(C(C(10 000))) mod 13<sup>8</sup>.
