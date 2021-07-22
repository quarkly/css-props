# overflow-x

The overflow-x CSS property sets what shows when content overflows a block-level element's left and right edges. This may be nothing, a scroll bar, or the overflow content.

## Values

<dl>
<dt>visible</dt>
<dd>Content is not clipped and may be rendered outside the padding box's left and right edges. If overflow-y is hidden, scroll or auto and this property is visible, it will implicitly compute to auto.</dd>
<dt>hidden</dt>
<dd>Content is clipped if necessary to fit horizontally in the padding box. No scrollbars are provided.</dd>
<dt>clip </dt>
<dd>Like for hidden, the content is clipped to the element's padding box. The difference between clip and hidden is that the clip keyword also forbids all scrolling, including programmatic scrolling. The box is not a scroll container, and does not start a new formatting context. If you wish to start a new formatting context, you can use display: flow-root to do so.</dd>
<dt>scroll</dt>
<dd>Content is clipped if necessary to fit horizontally in the padding box. Browsers display scrollbars whether or not any content is actually clipped. (This prevents scrollbars from appearing or disappearing when the content changes.) Printers may still print overflowing content.</dd>
<dt>auto</dt>
<dd>Depends on the user agent. If content fits inside the padding box, it looks the same as visible, but still establishes a new block-formatting context. Desktop browsers provide scrollbars if content overflows.</dd>
</dl>

## Examples

```
overflow-x="hidden"
overflow-x="scroll"
overflow-x="visible"
overflow-x="auto"
```
