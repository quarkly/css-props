## border-style

The border-style shorthand CSS property sets the line style for all four sides of an element's border.

## Values

<line-style>
Describes the style of the border. It can have the following values:

none
Like the hidden keyword, displays no border. Unless a background-image is set, the computed value of the same side's border-width will be 0, even if the specified value is something else. In the case of table cell and border collapsing, the none value has the lowest priority: if any other conflicting border is set, it will be displayed.

hidden
Like the none keyword, displays no border. Unless a background-image is set, the computed value of the same side's border-width will be 0, even if the specified value is something else. In the case of table cell and border collapsing, the hidden value has the highest priority: if any other conflicting border is set, it won't be displayed.

dotted
Displays a series of rounded dots. The spacing of the dots is not defined by the specification and is implementation-specific. The radius of the dots is half the computed value of the same side's border-width.

dashed
Displays a series of short square-ended dashes or line segments. The exact size and length of the segments are not defined by the specification and are implementation-specific.

solid
Displays a single, straight, solid line.

double
Displays two straight lines that add up to the pixel size defined by border-width.

groove
Displays a border with a carved appearance. It is the opposite of ridge.

ridge
Displays a border with an extruded appearance. It is the opposite of groove.

inset
Displays a border that makes the element appear embedded. It is the opposite of outset. When applied to a table cell with border-collapse set to collapsed, this value behaves like 
groove.

outset
Displays a border that makes the element appear embossed. It is the opposite of inset. When applied to a table cell with border-collapse set to collapsed, this value behaves like ridge.


## Examples

border-style: none;
border-style: dotted;
border-style: dashed;
border-style: solid;

