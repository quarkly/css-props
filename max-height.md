## max-height
The max-height CSS property sets the maximum height of an element. It prevents the used value of the height property from becoming larger than the value specified for max-height.

## Values

<length>
Defines the max-height as an absolute value.

<percentage>
Defines the max-height as a percentage of the containing block's height.

none
No limit on the size of the box.

max-content
The intrinsic preferred max-height.

min-content
The intrinsic minimum max-height.

fit-content(<length-percentage>)
Uses the fit-content formula with the available space replaced by the specified argument, i.e. min(max-content, max(min-content, argument)).

## Examples

max-height: 75%;

max-height: none;

max-height: 100vh;