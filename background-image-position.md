# position

The <position> (or <bg-position>) CSS data type denotes a two-dimensional coordinate used to set a location relative to an element box. It is used in the background-position and offset-anchor properties.


## Values

<dl>
<dd>The <position> data type is specified with one or two keywords, with optional offsets.

The keyword values are center, top, right, bottom, and left. Each keyword represents either an edge of the element's box or the center line between two edges. Depending on the context, center represents either the center between the left and right edges, or the center between the top and bottom edges.

If specified, an offset can be either a relative <percentage> value or an absolute <length> value. Positive values are offset towards the right or the bottom, whichever is appropriate. Negative values are offset in the opposite directions.

If only a single offset value is specified, it defines the x-coordinate, with the value for the other axis defaulting to center.</dd>
</dl>

## Examples

```
"center"
"left"
"center top"
"right 8.5%"
"bottom 12vmin right -6px"
```