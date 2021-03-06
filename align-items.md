# align-items

The CSS align-items property sets the align-self value on all direct children as a group. In Flexbox, it controls the alignment of items on the Cross Axis. In Grid Layout, it controls the alignment of items on the Block Axis within their grid area.

The interactive example below demonstrates some of the values for align-items using grid layout.

## Values

<dl>
<dt>normal</dt>
<dd>The effect of this keyword is dependent of the layout mode we are in:

-   In absolutely-positioned layouts, the keyword behaves like start on replaced absolutely-positioned boxes, and as stretch on all other absolutely-positioned boxes.
-   In static position of absolutely-positioned layouts, the keyword behaves as stretch.
-   For flex items, the keyword behaves as stretch.
-   For grid items, this keyword leads to a behavior similar to the one of stretch, except for boxes with an aspect ratio or an intrinsic sizes where it behaves like start.
The property doesn't apply to block-level boxes, and to table cells.</dd>
<dt>flex-start</dt>
<dd>The cross-start margin edges of the flex items are flushed with the cross-start edge of the line.</dd>
<dt>flex-end</dt>
<dd>The cross-end margin edges of the flex items are flushed with the cross-end edge of the line.</dd>
<dt>center</dt>
<dd>The flex items' margin boxes are centered within the line on the cross-axis. If the cross-size of an item is larger than the flex container, it will overflow equally in both directions.</dd>
<dt>start</dt>
<dd>The items are packed flush to each other toward the start edge of the alignment container in the appropriate axis.</dd>
<dt>end</dt>
<dd>The items are packed flush to each other toward the end edge of the alignment container in the appropriate axis.</dd>
<dt>self-start</dt>
<dd>The items are packed flush to the edge of the alignment container of the start side of the item, in the appropriate axis.</dd>
<dt>self-end</dt>
<dd>The items are packed flush to the edge of the alignment container of the end side of the item, in the appropriate axis.</dd>
<dt>baseline, first baseline, last baseline</dt>
<dd>All flex items are aligned such that their flex container baselines align. The item with the largest distance between its cross-start margin edge and its baseline is flushed with the cross-start edge of the line.</dd>
<dt>stretch</dt>
<dd>Flex items are stretched such that the cross-size of the item's margin box is the same as the line while respecting width and height constraints.</dd>
<dt>safe</dt>
<dd>Used alongside an alignment keyword. If the chosen keyword means that the item overflows the alignment container causing data loss, the item is instead aligned as if the alignment mode were start.</dd>
<dt>unsafe</dt>
<dd>Used alongside an alignment keyword. Regardless of the relative sizes of the item and alignment container and whether overflow which causes data loss might happen, the given alignment value is honored</dd>
</dl>

## Examples

```
align-items="center"
align-items="self-start"
align-items="flex-start"
align-items="baseline"
```
