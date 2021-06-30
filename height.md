## Height

The height CSS property specifies the height of an element. By default, the property defines the height of the content area. If box-sizing is set to border-box, however, it instead determines the height of the border area.

## Values

<length>
Defines the height as an absolute value.

<percentage>
Defines the height as a percentage of the containing block's height.

auto
The browser will calculate and select a height for the specified element.

max-content
The intrinsic preferred height.

min-content
The intrinsic minimum height.

fit-content(<length-percentage>)
Uses the fit-content formula with the available space replaced by the specified argument, i.e. min(max-content, max(min-content, <length-percentage>)).

## Examples

height: 50px;

height: 100vh;

height: 100px;

height: 50%;