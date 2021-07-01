## font-variant

The font-variant CSS shorthand property allows you to set all the font variants for a font.

You can also set the CSS Level 2 (Revision 1) values of font-variant, (that is, normal or small-caps), by using the font shorthand.


## Values

normal
Specifies a normal font face; each of the longhand properties has an initial value of normal. Longhand properties of font-variant are: font-variant-caps, font-variant-numeric, font-variant-alternates, font-variant-ligatures, and font-variant-east-asian.

none
Sets the value of the font-variant-ligatures to none and the values of the other longhand property as normal, their initial value.

<common-lig-values>, <discretionary-lig-values>, <historical-lig-values>, <contextual-alt-values>
Specifies the keywords related to the font-variant-ligatures longhand property. The possible values are: common-ligatures, no-common-ligatures, discretionary-ligatures, no-discretionary-ligatures, historical-ligatures, no-historical-ligatures, contextual, and no-contextual.

stylistic(), historical-forms, styleset(), character-variant(), swash(), ornaments(), annotation()
Specifies the keywords and functions related to the font-variant-alternates longhand property.

small-caps, all-small-caps, petite-caps, all-petite-caps, unicase, titling-caps
Specifies the keywords and functions related to the font-variant-caps longhand property.

<numeric-figure-values>, <numeric-spacing-values>, <numeric-fraction-values>, ordinal, slashed-zero
Specifies the keywords related to the font-variant-numeric longhand property. The possible values are:  lining-nums, oldstyle-nums, proportional-nums, tabular-nums, diagonal-fractions, stacked-fractions, ordinal, and slashed-zero.

<east-asian-variant-values>, <east-asian-width-values>, ruby
Specifies the keywords related to the font-variant-east-asian longhand property. The possible values are: jis78, jis83, jis90, jis04, simplified, traditional, full-width, proportional-width, ruby.

## Examples

font-variant: small-caps;
font-variant: common-ligatures small-caps;
font-variant: inherit;
font-variant: initial;