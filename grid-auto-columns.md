## grid-auto-columns

The grid-auto-columns CSS property specifies the size of an implicitly-created grid column track or pattern of tracks.


## Values

<length>
Is a non-negative length.

<percentage>
Is a non-negative <percentage> value relative to the block size of the grid container. If the block size of the grid container is indefinite, the percentage value is treated like auto.

<flex>
Is a non-negative dimension with the unit fr specifying the track’s flex factor. Each <flex>-sized track takes a share of the remaining space in proportion to its flex factor.
When appearing outside a minmax() notation, it implies an automatic minimum (i.e. minmax(auto, <flex>)).

max-content
Is a keyword representing the largest maximal content contribution of the grid items occupying the grid track.

min-content
Is a keyword representing the largest minimal content contribution of the grid items occupying the grid track.

minmax(min, max)
Is a functional notation that defines a size range greater than or equal to min and less than or equal to max. If max is smaller than min, then max is ignored and the function is treated as min. As a maximum, a <flex> value sets the track’s flex factor. As a minimum, it is treated as zero (or minimal content, if the grid container is sized under a minimal content constraint).

fit-content( [ <length> | <percentage> ] )
Represents the formula min(max-content, max(auto, argument)), which is calculated similar to auto (i.e. minmax(auto, max-content)), except that the track size is clamped at argument if it is greater than the auto minimum.

auto
Is a keyword that is identical to maximal content if it's a maximum. As a minimum it represents the largest minimum size (as specified by min-width/min-height) of the grid items occupying the grid track.


## Examples

grid-auto-columns: max-content;
grid-auto-columns: auto;
grid-auto-columns: 100px;
grid-auto-columns: 20cm;