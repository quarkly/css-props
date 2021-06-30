## background-clip

The background-clip CSS property sets whether an element's background extends underneath its border box, padding box, or content box.


## Values

border-box
The background extends to the outside edge of the border (but underneath the border in z-ordering).

padding-box
The background extends to the outside edge of the padding. No background is drawn beneath the border.

content-box
The background is painted within (clipped to) the content box.

text 
The background is painted within (clipped to) the foreground text.

## Examples

background-clip: border-box;
background-clip: padding-box;
background-clip: content-box;
background-clip: text;