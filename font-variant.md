# font-variant

The font-variant CSS shorthand property allows you to set all the font variants for a font.

You can also set the CSS Level 2 (Revision 1) values of font-variant, (that is, normal or small-caps), by using the font shorthand.


## Values

<dl>
<dt>normal</dt>
<dd>Specifies a normal font face; each of the longhand properties has an initial value of normal. Longhand properties of font-variant are: font-variant-caps, font-variant-numeric, font-variant-alternates, font-variant-ligatures, and font-variant-east-asian.</dd>

<dt>none</dt>
<dd>Sets the value of the font-variant-ligatures to none and the values of the other longhand property as normal, their initial value.</dd>

<dt><common-lig-values>, <discretionary-lig-values>, <historical-lig-values>, <contextual-alt-values></dt>
<dd>Specifies the keywords related to the font-variant-ligatures longhand property. The possible values are: common-ligatures, no-common-ligatures, discretionary-ligatures, no-discretionary-ligatures, historical-ligatures, no-historical-ligatures, contextual, and no-contextual.</dd>

<dt>stylistic(), historical-forms, styleset(), character-variant(), swash(), ornaments(), annotation()</dt>
<dd>Specifies the keywords and functions related to the font-variant-alternates longhand property.</dd>

<dt>small-caps, all-small-caps, petite-caps, all-petite-caps, unicase, titling-caps</dt>
<dd>Specifies the keywords and functions related to the font-variant-caps longhand property.</dd>

<dt><numeric-figure-values>, <numeric-spacing-values>, <numeric-fraction-values>, ordinal, slashed-zero</dt>
<dd>Specifies the keywords related to the font-variant-numeric longhand property. The possible values are:  lining-nums, oldstyle-nums, proportional-nums, tabular-nums, diagonal-fractions, stacked-fractions, ordinal, and slashed-zero.</dd>

<dt><east-asian-variant-values>, <east-asian-width-values>, ruby</dt>
<dd>Specifies the keywords related to the font-variant-east-asian longhand property. The possible values are: jis78, jis83, jis90, jis04, simplified, traditional, full-width, proportional-width, ruby.</dd>
</dl>

## Examples

```
font-variant="small-caps"
font-variant="common-ligatures small-caps"
font-variant="inherit"
font-variant="initial"
```