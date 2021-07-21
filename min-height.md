# min-height

The min-height CSS property sets the minimum height of an element. It prevents the used value of the height property from becoming smaller than the value specified for min-height.


## Values

<dl>
<dt><length></dt>
<dd>Defines the max-width as an absolute value.</dd>

<dt><percentage></dt>
<dd>Defines the max-width as a percentage of the containing block's width.</dd>

<dt>max-content</dt>
<dd>The intrinsic preferred max-width.</dd>

<dt>min-content</dt>
<dd>The intrinsic minimum max-width.</dd>

<dt>fit-content(<length-percentage>)</dt>
<dd>Uses the fit-content formula with the available space replaced by the specified argument, i.e. min(max-content, max(min-content, argument)).</dd>
</dl>

## Examples

```
min-height="75%"
min-height="0"
min-height="20px"
min-height="100vh"
```