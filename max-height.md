# max-height

The max-height CSS property sets the maximum height of an element. It prevents the used value of the height property from becoming larger than the value specified for max-height.


## Values

<dl>
<dt><length></dt>
<dd>Defines the max-height as an absolute value.</dd>

<dt><percentage></dt>
<dd>Defines the max-height as a percentage of the containing block's height.</dd>

<dt>none</dt>
<dd>No limit on the size of the box.</dd>

<dt>max-content</dt>
<dd>The intrinsic preferred max-height.</dd>

<dt>min-content</dt>
<dd>The intrinsic minimum max-height.</dd>

<dt>fit-content(<length-percentage>)</dt>
<dd>Uses the fit-content formula with the available space replaced by the specified argument, i.e. min(max-content, max(min-content, argument)).</dd>
</dl>

## Examples

```
max-height="75%"
max-height="none"
max-height="100vh"
```