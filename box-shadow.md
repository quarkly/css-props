# box-shadow

The box-shadow CSS property adds shadow effects around an element's frame. You can set multiple effects separated by commas. A box shadow is described by X and Y offsets relative to the element, blur and spread radius, and color.

## Values

<dl>
<dt>inset</dt>
<dd>If not specified (default), the shadow is assumed to be a drop shadow (as if the box were raised above the content).
The presence of the inset keyword changes the shadow to one inside the frame (as if the content was depressed inside the box). Inset shadows are drawn inside the border (even transparent ones), above the background, but below content.</dd>
<dt>&lt;offset-x&gt; &lt;offset-y&gt;</dt>
<dd>These are two &lt;length&gt; values to set the shadow offset. &lt;offset-x&gt; specifies the horizontal distance. Negative values place the shadow to the left of the element. &lt;offset-y&gt; specifies the vertical distance. Negative values place the shadow above the element. See &lt;length&gt; for possible units.
If both values are 0, the shadow is placed behind the element (and may generate a blur effect if &lt;blur-radius&gt; and/or &lt;spread-radius&gt; is set).</dd>
<dt>&lt;blur-radius&gt;</dt>
<dd>This is a third &lt;length&gt; value. The larger this value, the bigger the blur, so the shadow becomes bigger and lighter. Negative values are not allowed. If not specified, it will be 0 (the shadow's edge is sharp). The specification does not include an exact algorithm for how the blur radius should be calculated, however, it does elaborate as follows:
…for a long, straight shadow edge, this should create a color transition the length of the blur distance that is perpendicular to and centered on the shadow’s edge, and that ranges from the full shadow color at the radius endpoint inside the shadow to fully transparent at the endpoint outside it.</dd>
<dt>&lt;spread-radius&gt;</dt>
<dd>This is a fourth &lt;length&gt; value. Positive values will cause the shadow to expand and grow bigger, negative values will cause the shadow to shrink. If not specified, it will be 0 (the shadow will be the same size as the element).</dd>
<dt>&lt;color&gt;</dt>
<dd>See &lt;color&gt; values for possible keywords and notations.
If not specified, it defaults to &lt;color_value#currentcolor_keyword&gt;.</dd>
</dl>

## Examples

```
box-shadow="inset 0 -3em 3em rgba(0,0,0,0.1),
    0 0  0 2px rgb(255,255,255)
    0.3em 0.3em 1em rgba(0,0,0,0.3)"
```
