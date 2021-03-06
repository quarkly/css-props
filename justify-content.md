# justify-content

The CSS justify-content property defines how the browser distributes space between and around content items along the main-axis of a flex container, and the inline axis of a grid container.

The interactive example below demonstrates some of the values using Grid Layout.

## Values

<dl>
<dt>start</dt>
<dd>The items are packed flush to each other toward the start edge of the alignment container in the main axis.</dd>
<dt>end</dt>
<dd>The items are packed flush to each other toward the end edge of the alignment container in the main axis.</dd>
<dt>flex-start</dt>
<dd>The items are packed flush to each other toward the edge of the alignment container depending on the flex container's main-start side.
This only applies to flex layout items. For items that are not children of a flex container, this value is treated like start.</dd>
<dt>flex-end</dt>
<dd>The items are packed flush to each other toward the edge of the alignment container depending on the flex container's main-end side.
This only applies to flex layout items. For items that are not children of a flex container, this value is treated like end.</dd>
<dt>center</dt>
<dd>The items are packed flush to each other toward the center of the alignment container along the main axis.</dd>
<dt>left</dt>
<dd>The items are packed flush to each other toward the left edge of the alignment container. If the property’s axis is not parallel with the inline axis, this value behaves like start.</dd>
<dt>right</dt>
<dd>The items are packed flush to each other toward the right edge of the alignment container in the appropriate axis. If the property’s axis is not parallel with the inline axis, this value behaves like start.</dd>
<dt>normal</dt>
<dd>The items are packed in their default position as if no justify-content value was set. This value behaves as stretch in grid and flex containers.</dd>
<dt>baseline
first baseline
last baseline</dt>
<dd>Specifies participation in first- or last-baseline alignment: aligns the alignment baseline of the box’s first or last baseline set with the corresponding baseline in the shared first or last baseline set of all the boxes in its baseline-sharing group.
The fallback alignment for first baseline is start, the one for last baseline is end.</dd>
<dt>space-between</dt>
<dd>The items are evenly distributed within the alignment container along the main axis. The spacing between each pair of adjacent items is the same. The first item is flush with the main-start edge, and the last item is flush with the main-end edge.</dd>
<dt>space-around</dt>
<dd>The items are evenly distributed within the alignment container along the main axis. The spacing between each pair of adjacent items is the same. The empty space before the first and after the last item equals half of the space between each pair of adjacent items.</dd>
<dt>space-evenly</dt>
<dd>The items are evenly distributed within the alignment container along the main axis. The spacing between each pair of adjacent items, the main-start edge and the first item, and the main-end edge and the last item, are all exactly the same.</dd>
<dt>stretch</dt>
<dd>If the combined size of the items along the main axis is less than the size of the alignment container, any auto-sized items have their size increased equally (not proportionally), while still respecting the constraints imposed by max-height/max-width (or equivalent functionality), so that the combined size exactly fills the alignment container along the main axis.</dd>
<dd>Note: stretch is not supported by flexible boxes (flexbox).</dd>
<dt>safe</dt>
<dd>Used alongside an alignment keyword. If the chosen keyword means that the item overflows the alignment container causing data loss, the item is instead aligned as if the alignment mode were start.</dd>
<dt>unsafe</dt>
<dd>Used alongside an alignment keyword. Regardless of the relative sizes of the item and alignment container, and regardless of whether overflow which causes data loss might happen, the given alignment value is honored.</dd>
</dl>

## Examples

```
justify-content="center"
justify-content="space-between"
justify-content="flex-start"
justify-content="baseline"
```
