Quadtree encoding (a simple compression algorithm)
--------------------------------------------------

*Source: https://projecteuler.net/problem=287*


*Difficulty rating: 40%*

The quadtree encoding allows us to describe a 2<sup>N</sup>×2<sup>N</sup> black and white
image as a sequence of bits (0 and 1). Those sequences are to be read
from left to right like this:

-   the first bit deals with the complete 2<sup>N</sup>×2<sup>N</sup> region;
-   "0" denotes a split:\
    the current 2<sup>n</sup>×2<sup>n</sup> region is divided into 4 sub-regions of
    dimension 2<sup>n-1</sup>×2<sup>n-1</sup>,\
     the next bits contains the description of the top left, top right,
    bottom left and bottom right sub-regions - in that order;
-   "10" indicates that the current region contains only black pixels;
-   "11" indicates that the current region contains only white pixels.

Consider the following 4×4 image (colored marks denote places where a
split can occur):

![p287\_quadtree.gif](img/p287_quadtree.gif)

This image can be described by several sequences, for example :
"**00**10101010**0**1011111011**0**10101010", of length 30, or\
 "**0**10**0**101111101110", of length 16, which is the minimal sequence
for this image.

For a positive integer N, define D<sub>N</sub> as the 2<sup>N</sup>×2<sup>N</sup> image with the
following coloring scheme:

-   the pixel with coordinates x = 0, y = 0 corresponds to the bottom
    left pixel,
-   if (x - 2<sup>N-1<sup>)</sup>2</sup> + (y - 2<sup>N-1<sup>)</sup>2</sup> ≤ 2<sup>2N-2</sup> then the pixel is
    black,
-   otherwise the pixel is white.

What is the length of the minimal sequence describing D<sub>24</sub> ?
