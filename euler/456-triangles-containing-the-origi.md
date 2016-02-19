Triangles containing the origin II
----------------------------------

*Source: https://projecteuler.net/problem=456*


*Difficulty rating: 50%*

Define:\
x<sub>n</sub> = (1248<sup>n</sup> mod 32323) - 16161\
y<sub>n</sub> = (8421<sup>n</sup> mod 30103) - 15051\
 P<sub>n</sub> = {(x<sub>1</sub>, y<sub>1</sub>), (x<sub>2</sub>, y<sub>2</sub>), ..., (x<sub>n</sub>, y<sub>n</sub>)}

For example, P<sub>8</sub> = {(-14913, -6630), (-10161, 5625), (5226, 11896),
(8340, -10778), (15852, -5203), (-15165, 11295), (-1427, -14495),
(12407, 1060)}.

Let C(n) be the number of triangles whose vertices are in P<sub>n</sub> which
contain the origin in the interior.

Examples:\
 C(8) = 20\
 C(600) = 8950634\
 C(40 000) = 2666610948988

Find C(2 000 000).
