Subsequence of Thue-Morse sequence
----------------------------------

*Source: https://projecteuler.net/problem=361*


*Difficulty rating: 90%*

The **Thue-Morse sequence** {T<sub>n</sub>} is a binary sequence satisfying:

-   T<sub>0</sub> = 0
-   T<sub>2n</sub> = T<sub>n</sub>
-   T<sub>2n+1</sub> = 1 - T<sub>n</sub>

The first several terms of {T<sub>n</sub>} are given as follows:\
 01101001100101101001011001101001....

We define {A<sub>n</sub>} as the sorted sequence of integers such that the binary
expression of each element appears as a subsequence in {T<sub>n</sub>}.\
 For example, the decimal number 18 is expressed as 10010 in binary.
10010 appears in {T<sub>n</sub>} (T<sub>8</sub> to T<sub>12</sub>), so 18 is an element of {A<sub>n</sub>}.\
 The decimal number 14 is expressed as 1110 in binary. 1110 never
appears in {T<sub>n</sub>}, so 14 is not an element of {A<sub>n</sub>}.

The first several terms of A<sub>n</sub> are given as follows:\

  ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ----
  n    A<sub>n</sub>
  0    0
  1    1
  2    2
  3    3
  4    4
  5    5
  6    6
  7    9
  8    10
  9    11
  10   12
  11   13
  12   18
  …    …
  ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ----

We can also verify that A<sub>100</sub> = 3251 and A<sub>1000</sub> = 80852364498.

Find the last 9 digits of
![p361\_Thue-Morse1.gif](img/p361_Thue-Morse1.gif).
