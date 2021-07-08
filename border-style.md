# border-style

The border-style shorthand CSS property sets the line style for all four sides of an element's border.


## Values

<dl>
<dt><line-style></dt>
<dd>Describes the style of the border. It can have the following values:</dd>

<dt>none</dt>
<dd>Like the hidden keyword, displays no border. Unless a background-image is set, the computed value of the same side's border-width will be 0, even if the specified value is something else. In the case of table cell and border collapsing, the none value has the lowest priority: if any other conflicting border is set, it will be displayed.</dd>

<dt>hidden</dt>
<dd>Like the none keyword, displays no border. Unless a background-image is set, the computed value of the same side's border-width will be 0, even if the specified value is something else. In the case of table cell and border collapsing, the hidden value has the highest priority: if any other conflicting border is set, it won't be displayed.</dd>

<dt>dotted</dt>
<dd>Displays a series of rounded dots. The spacing of the dots is not defined by the specification and is implementation-specific. The radius of the dots is half the computed value of the same side's border-width.</dd>

<dt>dashed</dt>
<dd>Displays a series of short square-ended dashes or line segments. The exact size and length of the segments are not defined by the specification and are implementation-specific.</dd>

<dt>solid</dt>
<dd>Displays a single, straight, solid line.</dd>

<dt>double</dt>
<dd>Displays two straight lines that add up to the pixel size defined by border-width.</dd>

<dt>groove</dt>
<dd>Displays a border with a carved appearance. It is the opposite of ridge.</dd>

<dt>ridge</dt>
<dd>Displays a border with an extruded appearance. It is the opposite of groove.</dd>

<dt>inset</dt>
<dd>Displays a border that makes the element appear embedded. It is the opposite of outset. When applied to a table cell with border-collapse set to collapsed, this value behaves like groove.</dd>

<dt>outset</dt>
<dd>Displays a border that makes the element appear embossed. It is the opposite of inset. When applied to a table cell with border-collapse set to collapsed, this value behaves like ridge.</dd>
</dl>

## Examples

```
border-style="none"
border-style="dotted"
border-style="dashed"
border-style="solid"
```
