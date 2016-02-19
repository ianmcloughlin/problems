Weak Goodstein sequence
-----------------------

*Source: https://projecteuler.net/problem=396*


*Difficulty rating: 40%*

For any positive integer n, the **nth weak Goodstein sequence** {g<sub>1</sub>,
g<sub>2</sub>, g<sub>3</sub>, ...} is defined as:

-   g<sub>1</sub> = n
-   for k \> 1, g<sub>k</sub> is obtained by writing g<sub>k-1</sub> in base k,
    interpreting it as a base k + 1 number, and subtracting 1.

The sequence terminates when g<sub>k</sub> becomes 0.

For example, the 6th weak Goodstein sequence is {6, 11, 17, 25, ...}:

-   g<sub>1</sub> = 6.
-   g<sub>2</sub> = 11 since 6 = 110<sub>2</sub>, 110<sub>3</sub> = 12, and 12 - 1 = 11.
-   g<sub>3</sub> = 17 since 11 = 102<sub>3</sub>, 102<sub>4</sub> = 18, and 18 - 1 = 17.
-   g<sub>4</sub> = 25 since 17 = 101<sub>4</sub>, 101<sub>5</sub> = 26, and 26 - 1 = 25.

and so on.

It can be shown that every weak Goodstein sequence terminates.

Let G(n) be the number of nonzero elements in the nth weak Goodstein
sequence.\
 It can be verified that G(2) = 3, G(4) = 21 and G(6) = 381.\
 It can also be verified that ΣG(n) = 2517 for 1 ≤ n \< 8.

Find the last 9 digits of ΣG(n) for 1 ≤ n \< 16.
