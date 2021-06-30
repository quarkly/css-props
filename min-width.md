## min-width
The min-width CSS property sets the minimum width of an element. It prevents the used value of the width property from becoming smaller than the value specified for min-width.

## Values

<length>
Defines the min-width as an absolute value.

<percentage>
Defines the min-width as a percentage of the containing block's width.

auto
The browser will calculate and select a min-width for the specified element.

max-content
The intrinsic preferred min-width.

min-content
The intrinsic minimum min-width.

fit-content(<length-percentage>)
Uses the fit-content formula with the available space replaced by the specified argument, i.e. min(max-content, max(min-content, argument)).

## Examples

min-width: 75%;

min-width: 0;

min-width: 50px;