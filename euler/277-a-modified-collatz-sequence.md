A Modified Collatz sequence
---------------------------

*Source: https://projecteuler.net/problem=277*


*Difficulty rating: 35%*

A modified Collatz sequence of integers is obtained from a starting
value a<sub>1</sub> in the following way:

a<sub>n+1</sub> = a<sub>n</sub>/3 if a<sub>n</sub> is divisible by 3. We shall denote this as a
large downward step, "D".

a<sub>n+1</sub> = (4a<sub>n</sub> + 2)/3 if a<sub>n</sub> divided by 3 gives a remainder of 1. We
shall denote this as an upward step, "U".

a<sub>n+1</sub> = (2a<sub>n</sub> - 1)/3 if a<sub>n</sub> divided by 3 gives a remainder of 2. We
shall denote this as a small downward step, "d".

The sequence terminates when some a<sub>n</sub> = 1.

Given any integer, we can list out the sequence of steps.\
 For instance if a<sub>1</sub>=231, then the sequence
{a<sub>n</sub>}={231,77,51,17,11,7,10,14,9,3,1} corresponds to the steps
"DdDddUUdDD".

Of course, there are other sequences that begin with that same sequence
"DdDddUUdDD....".\
 For instance, if a<sub>1</sub>=1004064, then the sequence is
DdDddUUdDDDdUDUUUdDdUUDDDUdDD.\
 In fact, 1004064 is the smallest possible a<sub>1</sub> \> 10<sup>6</sup> that begins
with the sequence DdDddUUdDD.

What is the smallest a<sub>1</sub> \> 10<sup>15</sup> that begins with the sequence
"UDDDUdddDDUDDddDdDddDDUDDdUUDd"?
