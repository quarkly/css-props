## min-height
The min-height CSS property sets the minimum height of an element. It prevents the used value of the height property from becoming smaller than the value specified for min-height.

## Values

<length>
Defines the min-height as an absolute value.

<percentage>
Defines the min-height as a percentage of the containing block's height.

auto
The browser will calculate and select a min-height for the specified element.

max-content
The intrinsic preferred min-height.

min-content
The intrinsic minimum min-height.

fit-content(<length-percentage>)
Uses the fit-content formula with the available space replaced by the specified argument, i.e. min(max-content, max(min-content, argument)).

## Examples

min-height: 75%;

min-height: 0;

min-height: 20px;

min-height: 100vh;