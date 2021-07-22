# white-space

The white-space CSS property sets how white space inside an element is handled.

## Values

<dl>
<dt>normal</dt>
<dd>Sequences of white space are collapsed. Newline characters in the source are handled the same as other white space. Lines are broken as necessary to fill line boxes.</dd>
<dt>nowrap</dt>
<dd>Collapses white space as for normal, but suppresses line breaks (text wrapping) within the source.</dd>
<dt>pre</dt>
<dd>Sequences of white space are preserved. Lines are only broken at newline characters in the source and at &lt;br&gt; elements.</dd>
<dt>pre-wrap</dt>
<dd>Sequences of white space are preserved. Lines are broken at newline characters, at &lt;br&gt;, and as necessary to fill line boxes.</dd>
<dt>pre-line</dt>
<dd>Sequences of white space are collapsed. Lines are broken at newline characters, at &lt;br&gt;, and as necessary to fill line boxes.</dd>
<dt>break-spaces</dt>
<dd>The behavior is identical to that of pre-wrap, except that:
Any sequence of preserved white space always takes up space, including at the end of the line.
A line breaking opportunity exists after every preserved white space character, including between white space characters.
Such preserved spaces take up space and do not hang, and thus affect the box’s intrinsic sizes (min-content size and max-content size).</dd>
</dl>

## Examples

```
white-space="pre-wrap"
white-space="pre"
white-space="normal"
```
