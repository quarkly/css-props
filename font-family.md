# font-family

The font-family CSS property specifies a prioritized list of one or more font family names and/or generic family names for the selected element.


## Values

<dl>
<dt><family-name></dt>
<dd>The name of a font family. For example, "Times" and "Helvetica" are font families. Font family names containing whitespace should be quoted. For example: "Comic Sans MS".</dd>

<dt><generic-name></dt>
<dd>Generic font families are a fallback mechanism, a means of preserving some of the style sheet author's intent when none of the specified fonts are available. Generic family names are keywords and must not be quoted. A generic font family should be the last item in the list of font family names. The following keywords are defined:</dd>

<dt>serif</dt>
<dd>Glyphs have finishing strokes, flared or tapering ends, or have actual serifed endings.

For example: Lucida Bright, Lucida Fax, Palatino, Palatino Linotype, Palladio, URW Palladio, serif.</dd>

<dt>sans-serif</dt>
<dd>Glyphs have stroke endings that are plain.

For example: Open Sans, Fira Sans, Lucida Sans, Lucida Sans Unicode, Trebuchet MS, Liberation Sans, Nimbus Sans L, sans-serif.</dd>

<dt>monospace</dt>
<dd>All glyphs have the same fixed width.

For example: Fira Mono, DejaVu Sans Mono, Menlo, Consolas, Liberation Mono, Monaco, Lucida Console, monospace.</dd>

<dt>cursive</dt>
<dd>Glyphs in cursive fonts generally have either joining strokes or other cursive characteristics beyond those of italic typefaces. The glyphs are partially or completely connected, and the result looks more like handwritten pen or brush writing than printed letterwork.

For example: Brush Script MT, Brush Script Std, Lucida Calligraphy, Lucida Handwriting, Apple Chancery, cursive.</dd>

<dt>fantasy</dt>
<dd>Fantasy fonts are primarily decorative fonts that contain playful representations of characters.

For example: Papyrus, Herculanum, Party LET, Curlz MT, Harrington, fantasy.</dd>

<dt>system-ui</dt>
<dd>Glyphs are taken from the default user interface font on a given platform. Because typographic traditions vary widely across the world, this generic is provided for typefaces that don't map cleanly into the other generics.</dd>

<dt>ui-serif</dt>
<dd>The default user interface serif font.</dd>

<dt>ui-sans-serif</dt>
<dd>The default user interface sans-serif font.</dd>

<dt>ui-monospace</dt>
<dd>The default user interface monospace font.</dd>

<dt>ui-rounded</dt>
<dd>The default user interface font that has rounded features.</dd>

<dt>math</dt>
<dd>This is for the particular stylistic concerns of representing mathematics: superscript and subscript, brackets that cross several lines, nesting expressions, and double struck glyphs with distinct meanings.</dd>
</dl>

## Examples

```
font-family=""Goudy Bookletter 1911", sans-serif"
font-family="Gill Sans Extrabold, sans-serif"
```