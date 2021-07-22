# font-size

The font-size CSS property sets the size of the font. Changing the font size also updates the sizes of the font size-relative &lt;length&gt; units, such as em, ex, and so forth.

## Values

<dl>
<dt>xx-small, x-small, small, medium, large, x-large, xx-large, xxx-large</dt>
<dd>Absolute-size keywords, based on the user's default font size (which is medium).</dd>
<dt>larger, smaller</dt>
<dd>Relative-size keywords. The font will be larger or smaller relative to the parent element's font size, roughly by the ratio used to separate the absolute-size keywords above.</dd>
<dt>&lt;length&gt;</dt>
<dd>A positive &lt;length&gt; value. For most font-relative units (such as em and ex), the font size is relative to the parent element's font size.
For font-relative units that are root-based (such as rem), the font size is relative to the size of the font used by the &lt;html&gt; (root) element.</dd>
<dt>&lt;percentage&gt;</dt>
<dd>A positive &lt;percentage&gt; value, relative to the parent element's font size.</dd>
</dl>

## Examples

```
font-size="xx-small"
font-size="larger"
font-size="24pt"
font-size="200%"
```
