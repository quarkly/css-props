## cursor

The cursor CSS property sets the type of mouse cursor, if any, to show when the mouse pointer is over an element.


## Values

<url>
A url(…) or a comma separated list url(…), url(…), …, pointing to an image file. More than one url() may be provided as fallbacks, in case some cursor image types are not supported. A non-URL fallback (one or more of the keyword values) must be at the end of the fallback list. See Using URL values for the cursor property for more details.

<x> <y> 
Optional x- and y-coordinates. Two unitless nonnegative numbers less than 32.
Keyword values


## Examples

cursor: pointer;
cursor: auto;
cursor: url(hand.cur), pointer;