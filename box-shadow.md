# box-shadow

The box-shadow CSS property adds shadow effects around an element's frame. You can set multiple effects separated by commas. A box shadow is described by X and Y offsets relative to the element, blur and spread radius, and color.


## Values

<dl>
<dt>inset</dt>
<dd>If not specified (default), the shadow is assumed to be a drop shadow (as if the box were raised above the content).
The presence of the inset keyword changes the shadow to one inside the frame (as if the content was depressed inside the box). Inset shadows are drawn inside the border (even transparent ones), above the background, but below content.</dd>

<dt><offset-x> <offset-y></dt>
<dd>These are two <length> values to set the shadow offset. <offset-x> specifies the horizontal distance. Negative values place the shadow to the left of the element. <offset-y> specifies the vertical distance. Negative values place the shadow above the element. See <length> for possible units.
If both values are 0, the shadow is placed behind the element (and may generate a blur effect if <blur-radius> and/or <spread-radius> is set).</dd>

<dt><blur-radius></dt>
<dd>This is a third <length> value. The larger this value, the bigger the blur, so the shadow becomes bigger and lighter. Negative values are not allowed. If not specified, it will be 0 (the shadow's edge is sharp). The specification does not include an exact algorithm for how the blur radius should be calculated, however, it does elaborate as follows:
…for a long, straight shadow edge, this should create a color transition the length of the blur distance that is perpendicular to and centered on the shadow’s edge, and that ranges from the full shadow color at the radius endpoint inside the shadow to fully transparent at the endpoint outside it.</dd>

<dt><spread-radius></dt>
<dd>This is a fourth <length> value. Positive values will cause the shadow to expand and grow bigger, negative values will cause the shadow to shrink. If not specified, it will be 0 (the shadow will be the same size as the element).</dd>

<dt><color></dt>
<dd>See <color> values for possible keywords and notations.
If not specified, it defaults to <color_value#currentcolor_keyword>.</dd>
</dl>

## Examples

```
box-shadow="inset 0 -3em 3em rgba(0,0,0,0.1),
    0 0  0 2px rgb(255,255,255)
    0.3em 0.3em 1em rgba(0,0,0,0.3)"
```