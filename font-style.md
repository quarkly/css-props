# font-style

The font-style CSS property sets whether a font should be styled with a normal, italic, or oblique face from its font-family.


## Values

<dl>
<dt>normal</dt>
<dd>Selects a font that is classified as normal within a font-family.</dd>

<dt>italic</dt>
<dd>Selects a font that is classified as italic. If no italic version of the face is available, one classified as oblique is used instead. If neither is available, the style is artificially simulated.</dd>

<dt>oblique</dt>
<dd>Selects a font that is classified as oblique. If no oblique version of the face is available, one classified as italic is used instead. If neither is available, the style is artificially simulated.</dd>

<dt>oblique <angle></dt>
<dd>Selects a font classified as oblique, and additionally specifies an angle for the slant of the text. If one or more oblique faces are available in the chosen font family, the one that most closely matches the specified angle is chosen. If no oblique faces are available, the browser will synthesize an oblique version of the font by slanting a normal face by the specified amount. Valid values are degree values of -90deg to 90deg inclusive. If an angle is not specified, an angle of 14 degrees is used. Positive values are slanted to the end of the line, while negative values are slanted towards the beginning.</dd>

<dd>In general, for a requested angle of 14 degrees or greater, larger angles are preferred; otherwise,
smaller angles are preferred (see the spec's font matching section for the precise algorithm).</dd>
</dl>

## Examples

```
font-style="italic"
font-style="normal"
```