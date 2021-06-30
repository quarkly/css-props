## line-height

The line-height CSS property sets the height of a line box. It's commonly used to set the distance between lines of text. On block-level elements, it specifies the minimum height of line boxes within the element. On non-replaced inline elements, it specifies the height that is used to calculate line box height.


## Values

normal
Depends on the user agent. Desktop browsers (including Firefox) use a default value of roughly 1.2, depending on the element's font-family.

<number> (unitless)
The used value is this unitless <number> multiplied by the element's own font size. The computed value is the same as the specified <number>. In most cases, this is the preferred way to set line-height and avoid unexpected results due to inheritance.

<length>
The specified <length> is used in the calculation of the line box height. Values given in em units may produce unexpected results (see example below).

<percentage>
Relative to the font size of the element itself. The computed value is this <percentage> multiplied by the element's computed font size. Percentage values may produce unexpected results (see the second example below).

-moz-block-height 
Sets the line height to the content height of the current block.

## Examples

line-height: 1.2;
line-height: 1.2em;
line-height: 120%;
font: 10pt/1.2  Georgia,"Bitstream Charter",serif;