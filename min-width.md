# min-width

The min-width CSS property sets the minimum width of an element. It prevents the used value of the width property from becoming smaller than the value specified for min-width.

## Values

<dl>
<dt>&lt;length&gt;</dt>
<dd>Defines the max-width as an absolute value.</dd>
<dt>&lt;percentage&gt;</dt>
<dd>Defines the max-width as a percentage of the containing block's width.</dd>
<dt>max-content</dt>
<dd>The intrinsic preferred max-width.</dd>
<dt>min-content</dt>
<dd>The intrinsic minimum max-width.</dd>
<dt>fit-content(&lt;length-percentage&gt;)</dt>
<dd>Uses the fit-content formula with the available space replaced by the specified argument, i.e. min(max-content, max(min-content, argument)).</dd>
</dl>

## Examples

```
min-width="75%"
min-width="0"
min-width="50px"
```
