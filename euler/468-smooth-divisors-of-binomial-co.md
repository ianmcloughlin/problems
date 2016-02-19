Smooth divisors of binomial coefficients
----------------------------------------

*Source: https://projecteuler.net/problem=468*


*Difficulty rating: 70%*

An integer is called **B-smooth** if none of its prime factors is
greater than B.

Let S<sub>B</sub>(n) be the largest B-smooth divisor of n.\
 Examples:\
 S<sub>1</sub>(10) = 1\
 S<sub>4</sub>(2100) = 12\
 S<sub>17</sub>(2496144) = 5712

Define F(n) = ∑<sub>1≤B≤n</sub> ∑<sub>0≤r≤n</sub> S<sub>B</sub>(C(n,r)). Here, C(n,r) denotes the
binomial coefficient.\
 Examples:\
 F(11) = 3132\
 F(1 111) mod 1 000 000 993 = 706036312\
 F(111 111) mod 1 000 000 993 = 22156169

Find F(11 111 111) mod 1 000 000 993.
