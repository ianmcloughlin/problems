Bézier Curves
-------------

*Source: https://projecteuler.net/problem=363*


*Difficulty rating: 35%*

A cubic Bézier curve is defined by four points: P<sub>0</sub>, P<sub>1</sub>, P<sub>2</sub> and
P<sub>3</sub>.

![p363\_bezier.png](img/p363_bezier.png)

The curve is constructed as follows:\
 On the segments P<sub>0</sub>P<sub>1</sub>, P<sub>1</sub>P<sub>2</sub> and P<sub>2</sub>P<sub>3</sub> the points Q<sub>0</sub>,Q<sub>1</sub>
and Q<sub>2</sub> are drawn such that\
 P<sub>0</sub>Q<sub>0</sub> / P<sub>0</sub>P<sub>1</sub> = P<sub>1</sub>Q<sub>1</sub> / P<sub>1</sub>P<sub>2</sub> = P<sub>2</sub>Q<sub>2</sub> / P<sub>2</sub>P<sub>3</sub> = t (t
in [0,1]).\
 On the segments Q<sub>0</sub>Q<sub>1</sub> and Q<sub>1</sub>Q<sub>2</sub> the points R<sub>0</sub> and R<sub>1</sub> are
drawn such that\
 Q<sub>0</sub>R<sub>0</sub> / Q<sub>0</sub>Q<sub>1</sub> = Q<sub>1</sub>R<sub>1</sub> / Q<sub>1</sub>Q<sub>2</sub> = t for the same value of t.\
 On the segment R<sub>0</sub>R<sub>1</sub> the point B is drawn such that R<sub>0</sub>B / R<sub>0</sub>R<sub>1</sub>
= t for the same value of t.\
 The Bézier curve defined by the points P<sub>0</sub>, P<sub>1</sub>, P<sub>2</sub>, P<sub>3</sub> is the
locus of B as Q<sub>0</sub> takes all possible positions on the segment
P<sub>0</sub>P<sub>1</sub>.\
 (Please note that for all points the value of t is the same.)

At [this (external) web
address](http://home.kpn.nl/hklein/bezier/bezier.html) you will find an
applet that allows you to drag the points P<sub>0</sub>, P<sub>1</sub>, P<sub>2</sub> and P<sub>3</sub> to
see what the Bézier curve (green curve) defined by those points looks
like. You can also drag the point Q<sub>0</sub> along the segment P<sub>0</sub>P<sub>1</sub>.

From the construction it is clear that the Bézier curve will be tangent
to the segments P<sub>0</sub>P<sub>1</sub> in P<sub>0</sub> and P<sub>2</sub>P<sub>3</sub> in P<sub>3</sub>.

A cubic Bézier curve with P<sub>0</sub>=(1,0), P<sub>1</sub>=(1,v), P<sub>2</sub>=(v,1) and
P<sub>3</sub>=(0,1) is used to approximate a quarter circle.\
 The value v \> 0 is chosen such that the area enclosed by the lines
OP<sub>0</sub>, OP<sub>3</sub> and the curve is equal to <sup>π</sup>/<sub>4</sub> (the area of the quarter
circle).

By how many percent does the length of the curve differ from the length
of the quarter circle?

  ------------------------ ------------------------ ------------------------
  That is, if L is the
  length of the curve,
  calculate 100 ×
  L − π/2
  π/2
  ------------------------ ------------------------ ------------------------

Give your answer rounded to 10 digits behind the decimal point.
