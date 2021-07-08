# grid-template-columns

The grid-template-columns CSS property defines the line names and track sizing functions of the grid columns.


## Values

<dl>
<dt>none</dt>
<dd>Indicates that there is no explicit grid. Any columns will be implicitly generated and their size will be determined by the grid-auto-columns property.</dd>

<dt>[linename]</dt>
<dd>A <custom-ident> specifying a name for the line in that location. The ident may be any valid string other then the reserved words span and auto. Lines may have multiple names separated by a space inside the square brackets, for example [line-name-a line-name-b].</dd>

<dt><length></dt>
<dd>A non-negative length, giving the width of the column.</dd>

<dt><percentage></dt>
<dd>Is a non-negative <percentage> value relative to the inline size of the grid container. If the size of the grid container depends on the size of its tracks, then the percentage must be treated as auto.
The intrinsic size contributions of the track may be adjusted to the size of the grid container and increase the final size of the track by the minimum amount that would result in honoring the percentage.</dd>

<dt><flex></dt>
<dd>Is a non-negative dimension with the unit fr specifying the track’s flex factor. Each <flex>-sized track takes a share of the remaining space in proportion to its flex factor.
When appearing outside a minmax() notation, it implies an automatic minimum (i.e. minmax(auto, <flex>)).</dd>

<dt>max-content</dt>
<dd>Is a keyword representing the largest maximal content contribution of the grid items occupying the grid track.</dd>

<dt>min-content</dt>
<dd>Is a keyword representing the largest minimal content contribution of the grid items occupying the grid track.</dd>

<dt>minmax(min, max)</dt>
<dd>Is a functional notation that defines a size range greater than or equal to min and less than or equal to max. If max is smaller than min, then max is ignored and the function is treated as min. As a maximum, a <flex> value sets the track’s flex factor. It is invalid as a minimum.</dd>

<dt>auto</dt>
<dd>As a maximum represents the largest max-content size of the items in that track.</dd>

<dd>As a minimum represents the largest minimum size of items in that track (specified by the min-width/min-height of the items). This is often, though not always, the min-content size.</dd>

<dd>If used outside of minmax() notation, auto represents the range between the minimum and maximum described above. This behaves similarly to minmax(min-content,max-content) in most cases.</dd>

<dt>Note:</dt>
<dd>auto track sizes (and only auto track sizes) can be stretched by the align-content and justify-content properties. Therefore by default, an auto sized track will take up any remaining space in the grid container.</dd>

<dt>fit-content( [ <length> | <percentage> ] )</dt>
<dd>Represents the formula min(max-content, max(auto, argument)), which is calculated similar to auto (i.e. minmax(auto, max-content)), except that the track size is clamped at argument if it is greater than the auto minimum.</dd>

<dt>repeat( [ <positive-integer> | auto-fill | auto-fit ] , <track-list> )</dt>
<dd>Represents a repeated fragment of the track list, allowing a large number of columns that exhibit a recurring pattern to be written in a more compact form.</dd>

<dt>masonry</dt>
<dd>The masonry value indicates that this axis should be laid out according to the masonry algorithm.</dd>

<dt>subgrid</dt>
<dd>The subgrid value indicates that the grid will adopt the spanned portion of its parent grid in that axis. Rather than being specified explicitly, the sizes of the grid rows/columns will be taken from the parent grid’s definition.</dd>
</dl>

## Examples

```
grid-template-columns="100px 1fr"
grid-template-columns="[linename] 100px"
grid-template-columns="[linename1] 100px [linename2 linename3]"
grid-template-columns="minmax(100px, 1fr)"
```