## overflow-y
The overflow-y CSS property sets what shows when content overflows a block-level element's top and bottom edges. This may be nothing, a scroll bar, or the overflow content.

## Values

visible
Content is not clipped and may be rendered outside the padding box's top and bottom edges.

hidden
Content is clipped if necessary to fit vertically in the padding box. No scrollbars are provided.

clip 
Like for hidden, the content is clipped to the element's padding box. The difference between clip and hidden is that the clip keyword also forbids all scrolling, including programmatic scrolling. The box is not a scroll container, and does not start a new formatting context. If you wish to start a new formatting context, you can use display: flow-root to do so.

scroll
Content is clipped if necessary to fit vertically in the padding box. Browsers display scrollbars whether or not any content is actually clipped. (This prevents scrollbars from appearing or disappearing when the content changes.) Printers may still print overflowing content.

auto
Depends on the user agent. If content fits inside the padding box, it looks the same as visible, but still establishes a new block-formatting context. Desktop browsers provide scrollbars if content overflows.

## Examples

overflow-y: hidden;
overflow-y: scroll;
overflow-y: visible;
overflow-y: auto;