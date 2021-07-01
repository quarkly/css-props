## background-position

The background-position CSS property sets the initial position for each background image. The position is relative to the position layer set by background-origin.


## Values

<position>
A <position>. A position defines an x/y coordinate, to place an item relative to the edges of an element's box. It can be defined using one to four values. If two non-keyword values are used, the first value represents the horizontal position and the second represents the vertical position. If only one value is specified, the second value is assumed to be center. If three or four values are used, the length-percentage values are offsets for the preceding keyword value(s).

1-value syntax: the value may be:

The keyword value center, which centers the image.
One of the keyword values top, left, bottom, right. This specifies an edge against which to place the item. The other dimension is then set to 50%, so the item is placed in the middle of the edge specified.
A <length> or <percentage>. This specifies the X coordinate relative to the left edge, with the Y coordinate set to 50%.

2-value syntax: one value defines X and the other defines Y. Each value may be:

One of the keyword values top, left, bottom, right. If left or right are given here, then this defines X and the other given value defines Y. If top or bottom are given, then this defines Y and the other value defines X.
A <length> or <percentage>. If the other value is left or right, then this value defines Y, relative to the top edge. If the other value is top or bottom, then this value defines X, relative to the left edge. If both values are <length> or <percentage> values, then the first defines X and the second Y.
Note that: If one value is top or bottom, then the other value may not be top or bottom. If one value is left or right, then the other value may not be left or right. This means, e.g., that top top and left right are not valid.
The default value is top left or 0% 0%.

3-value syntax: Two values are keyword values, and the third is the offset for the preceding value:

The first value is one of the keyword values top, left, bottom, right, or center. If left or right are given here, then this defines X. If top or bottom are given, then this defines Y and the other keyword value defines X.
The <length> or <percentage> value, if it is the second value, is the offset for the first value. If it is the third value, it is the offset for the second value.
The single length or percentage value is an offset for the keyword value that precedes it. The combination of one keyword with two <length> or <percentage> values is not valid.

4-value syntax: The first and third values are keyword value defining X and Y. The second and fourth values are offsets for the preceding X and Y keyword values:

The first value and third values one of the keyword values top, left, bottom, right. If left or right are given here, then this defines X. If top or bottom are given, then this defines Y and the other keyword value defines X.
The second and fourth values are <length> or <percentage> values. The second value is the offset for the first keyword. The fourth value is the offset for the second keyword.

## Examples

background-position: top;
background-position: bottom;
background-position: bottom 10px right 20px;
background-position: right 3em bottom 10px;