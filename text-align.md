# text-align

The text-align CSS property sets the horizontal alignment of the content inside a block element or table-cell box. This means it works like vertical-align but in the horizontal direction.


## Values

<dl>
<dt>start</dt>
<dd>The same as left if direction is left-to-right and right if direction is right-to-left.</dd>

<dt>end</dt>
<dd>The same as right if direction is left-to-right and left if direction is right-to-left.</dd>

<dt>left</dt>
<dd>The inline contents are aligned to the left edge of the line box.</dd>

<dt>right</dt>
<dd>The inline contents are aligned to the right edge of the line box.</dd>

<dt>center</dt>
<dd>The inline contents are centered within the line box.</dd>

<dt>justify</dt>
<dd>The inline contents are justified. Text should be spaced to line up its left and right edges to the left and right edges of the line box, except for the last line.</dd>

<dt>justify-all</dt>
<dd>Same as justify, but also forces the last line to be justified.</dd>

<dt>match-parent</dt>
<dd>Similar to inherit, but the values start and end are calculated according to the parent's direction and are replaced by the appropriate left or right value.</dd>

<dt><string></dt> 
<dd>When applied to a table cell, specifies the alignment character around which the cell's contents will align.</dd>
</dl>

## Examples

```
text-align="left"
text-align="right"
text-align="center"
text-align="justify"
```