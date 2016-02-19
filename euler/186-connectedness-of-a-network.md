Connectedness of a network
--------------------------

*Source: https://projecteuler.net/problem=186*


*Difficulty rating: 60%*

Here are the records from a busy telephone system with one million
users:


|RecNr                  |1                        |2|
|------------------------|------------------------|------------------------|
|Caller                   |200007                   |600183|
|Called                   |100053                   |500439|

The telephone number of the caller and the called number in record n are
Caller(n) = S<sub>2n-1</sub> and Called(n) = S<sub>2n</sub> where S<sub>1,2,3,...</sub> come from
the "Lagged Fibonacci Generator":

For 1 ≤ k ≤ 55, S<sub>k</sub> = [100003 - 200003k + 300007k<sup>3</sup>] (modulo 1000000)\
 For 56 ≤ k, S<sub>k</sub> = [S<sub>k-24</sub> + S<sub>k-55</sub>] (modulo 1000000)

If Caller(n) = Called(n) then the user is assumed to have misdialled and
the call fails; otherwise the call is successful.

From the start of the records, we say that any pair of users X and Y are
friends if X calls Y or vice-versa. Similarly, X is a friend of a friend
of Z if X is a friend of Y and Y is a friend of Z; and so on for longer
chains.

The Prime Minister's phone number is 524287. After how many successful
calls, not counting misdials, will 99% of the users (including the PM)
be a friend, or a friend of a friend etc., of the Prime Minister?
