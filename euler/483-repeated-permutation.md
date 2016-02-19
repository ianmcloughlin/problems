Repeated permutation
--------------------

*Source: https://projecteuler.net/problem=483*


*Difficulty rating: 100%*

We define a *permutation* as an operation that rearranges the order of
the elements {1, 2, 3, ..., n}. There are n! such permutations, one of
which leaves the elements in their initial order. For n = 3 we have 3! =
6 permutations:\
 - P~1~ = keep the initial order\
 - P~2~ = exchange the 1<sup>st</sup> and 2<sup>nd</sup> elements\
 - P~3~ = exchange the 1<sup>st</sup> and 3<sup>rd</sup> elements\
 - P~4~ = exchange the 2<sup>nd</sup> and 3<sup>rd</sup> elements\
 - P~5~ = rotate the elements to the right\
 - P~6~ = rotate the elements to the left

If we select one of these permutations, and we re-apply the same
permutation repeatedly, we eventually restore the initial order.\
For a permutation P~i~, let f(P~i~) be the number of steps required to
restore the initial order by applying the permutation P~i~ repeatedly.\
For n = 3, we obtain:\
- f(P~1~) = 1 : (1,2,3) → (1,2,3)\
- f(P~2~) = 2 : (1,2,3) → (2,1,3) → (1,2,3)\
- f(P~3~) = 2 : (1,2,3) → (3,2,1) → (1,2,3)\
- f(P~4~) = 2 : (1,2,3) → (1,3,2) → (1,2,3)\
- f(P~5~) = 3 : (1,2,3) → (3,1,2) → (2,3,1) → (1,2,3)\
- f(P~6~) = 3 : (1,2,3) → (2,3,1) → (3,1,2) → (1,2,3)

Let g(n) be the average value of f<sup>2</sup>(P~i~) over all permutations P~i~
of length n.\
g(3) = (1<sup>2</sup> + 2<sup>2</sup> + 2<sup>2</sup> + 2<sup>2</sup> + 3<sup>2</sup> + 3<sup>2</sup>)/3! = 31/6 ≈
5.166666667e0\
g(5) = 2081/120 ≈ 1.734166667e1\
g(20) = 12422728886023769167301/2432902008176640000 ≈ 5.106136147e3

Find g(350) and write the answer in scientific notation rounded to 10
significant digits, using a lowercase e to separate mantissa and
exponent, as in the examples above.
