## font-size

The font-size CSS property sets the size of the font. Changing the font size also updates the sizes of the font size-relative <length> units, such as em, ex, and so forth.


## Values

xx-small, x-small, small, medium, large, x-large, xx-large, xxx-large
Absolute-size keywords, based on the user's default font size (which is medium).

larger, smaller
Relative-size keywords. The font will be larger or smaller relative to the parent element's font size, roughly by the ratio used to separate the absolute-size keywords above.

<length>
A positive <length> value. For most font-relative units (such as em and ex), the font size is relative to the parent element's font size.
For font-relative units that are root-based (such as rem), the font size is relative to the size of the font used by the <html> (root) element.

<percentage>
A positive <percentage> value, relative to the parent element's font size.

## Examples

font-size: xx-small;
font-size: larger;
font-size: 24pt;
font-size: 200%;