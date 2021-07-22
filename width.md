# width

The width CSS property sets an element's width. By default, it sets the width of the content area, but if box-sizing is set to border-box, it sets the width of the border area.

## Values

<dl>
<dt>&lt;length&gt;</dt>
<dd>Defines the width as an absolute value.</dd>
<dt>&lt;percentage&gt;</dt>
<dd>Defines the width as a percentage of the containing block's width.</dd>
<dt>auto</dt>
<dd>The browser will calculate and select a width for the specified element.</dd>
<dt>max-content</dt>
<dd>The intrinsic preferred width.</dd>
<dt>min-content</dt>
<dd>The intrinsic minimum width.</dd>
<dt>fit-content(&lt;length-percentage&gt;)</dt>
<dd>Uses the fit-content formula with the available space replaced by the specified argument, i.e. min(max-content, max(min-content, &lt;length-percentage&gt;)).</dd>
</dl>

## Examples

```
width="300px"
width="25em"
width="75%"
width="max-content"
```
