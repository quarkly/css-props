## background-attachment

The background-attachment CSS property sets whether a background image's position is fixed within the viewport, or scrolls with its containing block.


## Values

fixed
The background is fixed relative to the viewport. Even if an element has a scrolling mechanism, the background doesn't move with the element. (This is not compatible with background-clip: text.)

local
The background is fixed relative to the element's contents. If the element has a scrolling mechanism, the background scrolls with the element's contents, and the background painting area and background positioning area are relative to the scrollable area of the element rather than to the border framing them.

scroll
The background is fixed relative to the element itself and does not scroll with its contents. (It is effectively attached to the element's border.)

## Examples

background-attachment: scroll;
background-attachment: fixed;
background-attachment: local;