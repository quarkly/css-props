## flex-direction
The flex-direction CSS property sets how flex items are placed in the flex container defining the main axis and the direction (normal or reversed).

## Values

The following values are accepted:

row
The flex container's main-axis is defined to be the same as the text direction. The main-start and main-end points are the same as the content 
direction.

row-reverse
Behaves the same as row but the main-start and main-end points are permuted.

column
The flex container's main-axis is the same as the block-axis. The main-start and main-end points are the same as the before and after points of the writing-mode.

column-reverse
Behaves the same as column but the main-start and main-end are permuted.

## Examples

flex-direction: row-reverse;
flex-direction: column-reverse;
flex-direction: column;
flex-direction: row;