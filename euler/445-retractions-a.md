Retractions A
-------------

*Source: https://projecteuler.net/problem=445*


*Difficulty rating: 50%*

For every integer n\>1, the family of functions f<sub>n,a,b</sub> is defined by
f<sub>n,a,b</sub>(x)≡ax+b mod n for a,b,x integer and 0\<a\<n, 0≤b\<n, 0≤x\<n.\
 We will call f<sub>n,a,b</sub> a *retraction* if
f<sub>n,a,b</sub>(f<sub>n,a,b</sub>(x))≡f<sub>n,a,b</sub>(x) mod n for every 0≤x\<n.\
 Let R(n) be the number of retractions for n.

You are given that\
 ∑ R(c) for c=C(100 000,k), and 1 ≤ k ≤99 999 ≡628701600 (mod 1 000 000
007).\
 (C(n,k) is the binomial coefficient).\

Find ∑ R(c) for c=C(10 000 000,k), and 1 ≤k≤ 9 999 999.\
 Give your answer modulo 1 000 000 007.
