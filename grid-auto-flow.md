# grid-auto-flow

The grid-auto-flow CSS property controls how the auto-placement algorithm works, specifying exactly how auto-placed items get flowed into the grid.

## Values

<dl>
<dt>row</dt>
<dd>Items are placed by filling each row in turn, adding new rows as necessary. If neither row nor column is provided, row is assumed.</dd>
<dt>column</dt>
<dd>tems are placed by filling each column in turn, adding new columns as necessary.</dd>
<dt>dense</dt>
<dd>"dense" packing algorithm attempts to fill in holes earlier in the grid, if smaller items come up later. This may cause items to appear out-of-order, when doing so would fill in holes left by larger items.
If it is omitted, a "sparse" algorithm is used, where the placement algorithm only ever moves "forward" in the grid when placing items, never backtracking to fill holes. This ensures that all of the auto-placed items appear "in order", even if this leaves holes that could have been filled by later items.</dd>
</dl>

## Examples

```
grid-auto-flow="row"
grid-auto-flow="column"
grid-auto-flow="dense"
grid-auto-flow="row dense"
```
