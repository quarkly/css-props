# height

The height CSS property specifies the height of an element. By default, the property defines the height of the content area. If box-sizing is set to border-box, however, it instead determines the height of the border area.

## Values

<dl>
<dt>&lt;length&gt;</dt>
<dd>Defines the height as an absolute value.</dd>
<dt>&lt;percentage&gt;</dt>
<dd>Defines the height as a percentage of the containing block's height.</dd>
<dt>auto</dt>
<dd>The browser will calculate and select a height for the specified element.</dd>
<dt>max-content</dt>
<dd>The intrinsic preferred height.</dd>
<dt>min-content</dt>
<dd>The intrinsic minimum height.</dd>
<dt>fit-content(&lt;length-percentage&gt;)</dt>
<dd>Uses the fit-content formula with the available space replaced by the specified argument, i.e. min(max-content, max(min-content, &lt;length-percentage&gt;)).</dd>
</dl>

## Examples

```
height="50px"
height="100vh"
height="100px"
height="50%"
```
