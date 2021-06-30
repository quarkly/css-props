## max-width
The max-width CSS property sets the maximum width of an element. It prevents the used value of the width property from becoming larger than the value specified by max-width.

## Values

<length>
Defines the max-width as an absolute value.

<percentage>
Defines the max-width as a percentage of the containing block's width.

none
No limit on the size of the box.

max-content
The intrinsic preferred max-width.

min-content
The intrinsic minimum max-width.

fit-content(<length-percentage>)
Uses the fit-content formula with the available space replaced by the specified argument, i.e. min(max-content, max(min-content, argument)).

## Examples

max-width: 150px;

max-width: 50%;