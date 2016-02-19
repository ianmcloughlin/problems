Retractions C
-------------

*Source: https://projecteuler.net/problem=447*


*Difficulty rating: 95%*

For every integer n\>1, the family of functions f<sub>n,a,b</sub> is defined by
f<sub>n,a,b</sub>(x)≡ax+b mod n for a,b,x integer and 0\<a\<n, 0≤b\<n, 0≤x\<n.\
 We will call f<sub>n,a,b</sub> a *retraction* if
f<sub>n,a,b</sub>(f<sub>n,a,b</sub>(x))≡f<sub>n,a,b</sub>(x) mod n for every 0≤x\<n.\
 Let R(n) be the number of retractions for n.

F(N)=∑R(n) for 2≤n≤N.\
 F(10<sup>7</sup>)≡638042271 (mod 1 000 000 007).

Find F(10<sup>14</sup>) (mod 1 000 000 007).
