## align-self

The align-self CSS property overrides a grid or flex item's align-items value. In Grid, it aligns the item inside the grid area. In Flexbox, it aligns the item on the cross axis.


## Values

auto
Computes to the parent's align-items value.

normal
The effect of this keyword is dependent of the layout mode we are in:
In absolutely-positioned layouts, the keyword behaves like start on replaced absolutely-positioned boxes, and as stretch on all other absolutely-positioned boxes.
In static position of absolutely-positioned layouts, the keyword behaves as stretch.
For flex items, the keyword behaves as stretch.
For grid items, this keyword leads to a behavior similar to the one of stretch, except for boxes with an aspect ratio or an intrinsic sizes where it behaves like start.
The property doesn't apply to block-level boxes, and to table cells.

self-start
Aligns the items to be flush with the edge of the alignment container corresponding to the item's start side in the cross axis.

self-end
Aligns the items to be flush with the edge of the alignment container corresponding to the item's end side in the cross axis.

flex-start
The cross-start margin edge of the flex item is flushed with the cross-start edge of the line.

flex-end
The cross-end margin edge of the flex item is flushed with the cross-end edge of the line.

center
The flex item's margin box is centered within the line on the cross-axis. If the cross-size of the item is larger than the flex container, it will overflow equally in both directions.

baseline
first baseline
last baseline
Specifies participation in first- or last-baseline alignment: aligns the alignment baseline of the box’s first or last baseline set with the corresponding baseline in the shared first or last baseline set of all the boxes in its baseline-sharing group.
The fallback alignment for first baseline is start, the one for last baseline is end.

stretch
If the combined size of the items along the cross axis is less than the size of the alignment container and the item is auto-sized, its size is increased equally (not proportionally), while still respecting the constraints imposed by max-height/max-width (or equivalent functionality), so that the combined size of all auto-sized items exactly fills the alignment container along the cross axis.

safe
If the size of the item overflows the alignment container, the item is instead aligned as if the alignment mode were start.

unsafe
Regardless of the relative sizes of the item and alignment container, the given alignment value is honored.


## Examples

align-self: center; /* Put the item around the center */
align-self: start; /* Put the item at the start */
align-self: end; /* Put the item at the end */
align-self: self-start; /* Align the item flush at the start */