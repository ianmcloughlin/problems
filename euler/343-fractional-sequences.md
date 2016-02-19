Fractional Sequences
--------------------

*Source: https://projecteuler.net/problem=343*


*Difficulty rating: 35%*

For any positive integer k, a finite sequence a<sub>i</sub> of fractions
x<sub>i</sub>/y<sub>i</sub> is defined by:\
 a<sub>1</sub> = 1/k and\
 a<sub>i</sub> = (x<sub>i-1</sub>+1)/(y<sub>i-1</sub>-1) reduced to lowest terms for i\>1.\
 When a<sub>i</sub> reaches some integer n, the sequence stops. (That is, when
y<sub>i</sub>=1.)\
 Define f(k) = n.\
 For example, for k = 20:

1/20 → 2/19 → 3/18 = 1/6 → 2/5 → 3/4 → 4/3 → 5/2 → 6/1 = 6

So f(20) = 6.

Also f(1) = 1, f(2) = 2, f(3) = 1 and Σf(k<sup>3</sup>) = 118937 for 1 ≤ k ≤ 100.

Find Σf(k<sup>3</sup>) for 1 ≤ k ≤ 2×10<sup>6</sup>.
