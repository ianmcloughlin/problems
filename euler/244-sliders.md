Sliders
-------

*Source: https://projecteuler.net/problem=244*

Published on Saturday, 9th May 2009, 02:00 pm; Solved by 881; Difficulty
rating: 70%

You probably know the game *Fifteen Puzzle*. Here, instead of numbered
tiles, we have seven red tiles and eight blue tiles.

A move is denoted by the uppercase initial of the direction (Left,
Right, Up, Down) in which the tile is slid, e.g. starting from
configuration (**S**), by the sequence **LULUR** we reach the
configuration (**E**):

  ------------------ ------------------ ------------------ ------------------
  (**S**)
  ![img/p244_start.gif](img/p244_start.gif)
  , (**E**)
  ![img/p244_example.gif](img/p244_example.gif)
  ------------------ ------------------ ------------------ ------------------

For each path, its checksum is calculated by (pseudocode):

checksum = 0
 checksum = (checksum × 243 + m<sub>1</sub>) mod 100 000 007
 checksum = (checksum × 243 + m<sub>2</sub>) mod 100 000 007
    …
 checksum = (checksum × 243 + m<sub>n</sub>) mod 100 000 007

where m<sub>k</sub> is the ASCII value of the k<sup>th</sup> letter in the move sequence
and the ASCII values for the moves are:

|**L**|**R**|
|--:|--:|
|76|82|

For the sequence **LULUR** given above, the checksum would be 19761398.

Now, starting from configuration (**S**), find all shortest ways to
reach configuration (**T**).

  ------------------ ------------------ ------------------ ------------------
  (**S**)
  ![img/p244_start.gif](img/p244_start.gif)
  , (**T**)
  ![p244\_target.gif](img/p_244_target.gif)
  ------------------ ------------------ ------------------ ------------------

What is the sum of all checksums for the paths having the minimal
length?
