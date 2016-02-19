Squares under a hyperbola
-------------------------

*Source: https://projecteuler.net/problem=247*

Published on Friday, 29th May 2009, 09:00 pm; Solved by 1013; Difficulty
rating: 65%

Consider the region constrained by 1 ≤ x and 0 ≤ y ≤ <sup>1</sup>/<sub>x</sub>.

Let S<sub>1</sub> be the largest square that can fit under the curve.\
 Let S<sub>2</sub> be the largest square that fits in the remaining area, and so
on.\
 Let the *index* of S<sub>n</sub> be the pair (left, below) indicating the number
of squares to the left of S<sub>n</sub> and the number of squares below S<sub>n</sub>.

![](img/p247_hypersquares.gif)

The diagram shows some such squares labelled by number.\
 S<sub>2</sub> has one square to its left and none below, so the index of S<sub>2</sub> is
(1,0).\
 It can be seen that the index of S<sub>32</sub> is (1,1) as is the index of
S<sub>50</sub>.\
 50 is the largest n for which the index of S<sub>n</sub> is (1,1).

What is the largest n for which the index of S<sub>n</sub> is (3,3)?
