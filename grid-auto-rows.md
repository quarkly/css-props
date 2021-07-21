# grid-auto-rows

The grid-auto-rows CSS property specifies the size of an implicitly-created grid row track or pattern of tracks.


## Values

<dl>
<dt><length></dt>
<dd>Is a non-negative length.</dd>

<dt><percentage></dt>
<dd>Is a non-negative <percentage> value relative to the block size of the grid container. If the block size of the grid container is indefinite, the percentage value is treated like auto.</dd>

<dt><flex></dt>
<dd>Is a non-negative dimension with the unit fr specifying the track’s flex factor. Each <flex>-sized track takes a share of the remaining space in proportion to its flex factor.
When appearing outside a minmax() notation, it implies an automatic minimum (i.e. minmax(auto, <flex>)).</dd>

<dt>max-content</dt>
<dd>Is a keyword representing the largest maximal content contribution of the grid items occupying the grid track.</dd>

<dt>min-content</dt>
<dd>Is a keyword representing the largest minimal content contribution of the grid items occupying the grid track.</dd>

<dt>minmax(min, max)</dt>
<dd>Is a functional notation that defines a size range greater than or equal to min and less than or equal to max. If max is smaller than min, then max is ignored and the function is treated as min. As a maximum, a <flex> value sets the track’s flex factor. As a minimum, it is treated as zero (or minimal content, if the grid container is sized under a minimal content constraint).</dd>

<dt>fit-content( [ <length> | <percentage> ] )</dt>
<dd>Represents the formula min(max-content, max(auto, argument)), which is calculated similar to auto (i.e. minmax(auto, max-content)), except that the track size is clamped at argument if it is greater than the auto minimum.</dd>

<dt>auto</dt>
<dd>Is a keyword that is identical to maximal content if it's a maximum. As a minimum it represents the largest minimum size (as specified by min-width/min-height) of the grid items occupying the grid track.
Note: auto track sizes (and only auto track sizes) can be stretched by the align-content and justify-content properties.</dd>
</dl>

## Examples

```
grid-auto-rows="100px"
grid-auto-rows="20cm"
grid-auto-rows="max-content"
grid-auto-rows="auto"
```