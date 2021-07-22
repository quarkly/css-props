# line-height

The line-height CSS property sets the height of a line box. It's commonly used to set the distance between lines of text. On block-level elements, it specifies the minimum height of line boxes within the element. On non-replaced inline elements, it specifies the height that is used to calculate line box height.

## Values

<dl>
<dt>normal</dt>
<dd>Depends on the user agent. Desktop browsers (including Firefox) use a default value of roughly 1.2, depending on the element's font-family.</dd>
<dt>&lt;number&gt; (unitless)</dt>
<dd>The used value is this unitless &lt;number&gt; multiplied by the element's own font size. The computed value is the same as the specified &lt;number&gt;. In most cases, this is the preferred way to set line-height and avoid unexpected results due to inheritance.</dd>
<dt>&lt;length&gt;</dt>
<dd>The specified &lt;length&gt; is used in the calculation of the line box height. Values given in em units may produce unexpected results (see example below).</dd>
<dt>&lt;percentage&gt;</dt>
<dd>Relative to the font size of the element itself. The computed value is this &lt;percentage&gt; multiplied by the element's computed font size. Percentage values may produce unexpected results (see the second example below).</dd>
<dt>-moz-block-height</dt>
<dd>Sets the line height to the content height of the current block.</dd>
</dl>

## Examples

```
line-height="1.2"
line-height="1.2em"
line-height="120%"
font="10pt/1.2  Georgia,"Bitstream Charter",serif"
```
