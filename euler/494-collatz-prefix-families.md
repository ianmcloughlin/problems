Collatz prefix families
-----------------------

*Source: https://projecteuler.net/problem=494*


*Difficulty rating: 100%*

The Collatz sequence is defined as: \$a\_{i+1} = \\left\\{
\\large{\\frac {a\_i} 2 \\atop 3 a\_i+1} {\\text{if }a\_i\\text{ is
even} \\atop \\text{if }a\_i\\text{ is odd}} \\right.\$.

The Collatz conjecture states that starting from any positive integer,
the sequence eventually reaches the cycle 1,4,2,1....\
 We shall define the sequence prefix p(n) for the Collatz sequence
starting with a<sub>1</sub> = n as the sub-sequence of all numbers not a power of
2 (2<sup>0</sup>=1 is considered a power of 2 for this problem). For example:\
p(13) = {13, 40, 20, 10, 5}\
p(8) = {}\
 Any number invalidating the conjecture would have an infinite length
sequence prefix.

Let S<sub>m</sub> be the set of all sequence prefixes of length m. Two sequences
{a<sub>1</sub>, a<sub>2</sub>, ..., a<sub>m</sub>} and {b<sub>1</sub>, b<sub>2</sub>, ..., b<sub>m</sub>} in S<sub>m</sub> are said to
belong to the same prefix family if a<sub>i</sub> \< a<sub>j</sub> if and only if b<sub>i</sub> \<
b<sub>j</sub> for all 1 ≤ i,j ≤ m.

For example, in S<sub>4</sub>, {6, 3, 10, 5} is in the same family as {454, 227,
682, 341}, but not {113, 340, 170, 85}.\
 Let f(m) be the number of distinct prefix families in S<sub>m</sub>.\
 You are given f(5) = 5, f(10) = 55, f(20) = 6771.

Find f(90).
