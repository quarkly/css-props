## width

The width CSS property sets an element's width. By default, it sets the width of the content area, but if box-sizing is set to border-box, it sets the width of the border area.


## Values

<length>
Defines the width as an absolute value.

<percentage>
Defines the width as a percentage of the containing block's width.

auto
The browser will calculate and select a width for the specified element.

max-content
The intrinsic preferred width.

min-content
The intrinsic minimum width.

fit-content(<length-percentage>)
Uses the fit-content formula with the available space replaced by the specified argument, i.e. min(max-content, max(min-content, <length-percentage>)).

## Examples

width: 300px;
width: 25em;
width: 75%;
width: max-content;