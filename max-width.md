# max-width

The max-width CSS property sets the maximum width of an element. It prevents the used value of the width property from becoming larger than the value specified by max-width.


## Values

<dl>
<dt><length></dt>
<dd>Defines the max-width as an absolute value.</dd>

<dt><percentage></dt>
<dd>Defines the max-width as a percentage of the containing block's width.</dd>

<dt>none</dt>
<dd>No limit on the size of the box.</dd>

<dt>max-content</dt>
<dd>The intrinsic preferred max-width.</dd>

<dt>min-content</dt>
<dd>The intrinsic minimum max-width.</dd>

<dt>fit-content(<length-percentage>)</dt>
<dd>Uses the fit-content formula with the available space replaced by the specified argument, i.e. min(max-content, max(min-content, argument)).</dd>
</dl>

## Examples

```
max-width="150px"
max-width="50%"
max-width="100vh"
```