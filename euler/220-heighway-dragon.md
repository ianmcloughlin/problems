Heighway Dragon
---------------

*Source: https://projecteuler.net/problem=220*


*Difficulty rating: 55%*

Let ***D***<sub>0</sub> be the two-letter string "Fa". For n≥1, derive ***D***<sub>n</sub>
from ***D***<sub>n-1</sub> by the string-rewriting rules:

"a" → "aRbFR"\
 "b" → "LFaLb"

Thus, ***D***<sub>0</sub> = "Fa", ***D***<sub>1</sub> = "FaRbFR", ***D***<sub>2</sub> =
"FaRbFRRLFaLbFR", and so on.

These strings can be interpreted as instructions to a computer graphics
program, with "F" meaning "draw forward one unit", "L" meaning "turn
left 90 degrees", "R" meaning "turn right 90 degrees", and "a" and "b"
being ignored. The initial position of the computer cursor is (0,0),
pointing up towards (0,1).

Then ***D***<sub>n</sub> is an exotic drawing known as the *Heighway Dragon* of
order *n*. For example, ***D***<sub>10</sub> is shown below; counting each "F" as
one step, the highlighted spot at (18,16) is the position reached after
500 steps.

![](img/p220.gif)

What is the position of the cursor after 10<sup>12</sup> steps in ***D***<sub>50</sub> ?\
 Give your answer in the form *x*,*y* with no spaces.
