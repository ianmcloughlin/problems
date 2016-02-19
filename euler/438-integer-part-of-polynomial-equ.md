Integer part of polynomial equation's solutions
-----------------------------------------------

*Source: https://projecteuler.net/problem=438*


*Difficulty rating: 95%*

For an n-tuple of integers t = (a<sub>1</sub>, ..., a<sub>n</sub>), let (x<sub>1</sub>, ..., x<sub>n</sub>)
be the solutions of the polynomial equation x<sup>n</sup> + a<sub>1</sub>x<sup>n-1</sup> +
a<sub>2</sub>x<sup>n-2</sup> + ... + a<sub>n-1</sub>x + a<sub>n</sub> = 0.

Consider the following two conditions:

-   x<sub>1</sub>, ..., x<sub>n</sub> are all real.
-   If x<sub>1</sub>, ..., x<sub>n</sub> are sorted, ⌊x<sub>i</sub>⌋ = i for 1 ≤ i ≤ n. (⌊·⌋: floor
    function.)

In the case of n = 4, there are 12 n-tuples of integers which satisfy
both conditions.\
 We define S(t) as the sum of the absolute values of the integers in t.\
 For n = 4 we can verify that ∑S(t) = 2087 for all n-tuples t which
satisfy both conditions.

Find ∑S(t) for n = 7.
