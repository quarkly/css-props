## text-align

The text-align CSS property sets the horizontal alignment of the content inside a block element or table-cell box. This means it works like vertical-align but in the horizontal direction.


## Values

start 
The same as left if direction is left-to-right and right if direction is right-to-left.

end 
The same as right if direction is left-to-right and left if direction is right-to-left.

left
The inline contents are aligned to the left edge of the line box.

right
The inline contents are aligned to the right edge of the line box.

center
The inline contents are centered within the line box.

justify
The inline contents are justified. Text should be spaced to line up its left and right edges to the left and right edges of the line box, except for the last line.

justify-all 
Same as justify, but also forces the last line to be justified.

match-parent 
Similar to inherit, but the values start and end are calculated according to the parent's direction and are replaced by the appropriate left or right value.

<string> 
When applied to a table cell, specifies the alignment character around which the cell's contents will align.

## Examples

text-align: left;
text-align: right;
text-align: center;
text-align: justify;