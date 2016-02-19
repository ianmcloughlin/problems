Steps in Euclid's algorithm
---------------------------

*Source: https://projecteuler.net/problem=433*


*Difficulty rating: 65%*

Let E(x<sub>0</sub>, y<sub>0</sub>) be the number of steps it takes to determine the
greatest common divisor of x<sub>0</sub> and y<sub>0</sub> with **Euclid's algorithm**.
More formally:\
x<sub>1</sub> = y<sub>0</sub>, y<sub>1</sub> = x<sub>0</sub> mod y<sub>0</sub>\
x<sub>n</sub> = y<sub>n-1</sub>, y<sub>n</sub> = x<sub>n-1</sub> mod y<sub>n-1</sub>\
 E(x<sub>0</sub>, y<sub>0</sub>) is the smallest n such that y<sub>n</sub> = 0.

We have E(1,1) = 1, E(10,6) = 3 and E(6,10) = 4.

Define S(N) as the sum of E(x,y) for 1 ≤ x,y ≤ N.\
 We have S(1) = 1, S(10) = 221 and S(100) = 39826.

Find S(5·10<sup>6</sup>).
