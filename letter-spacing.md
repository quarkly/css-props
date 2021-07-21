# letter-spacing

The letter-spacing CSS property sets the horizontal spacing behavior between text characters. This value is added to the natural spacing between characters while rendering the text. Positive values of letter-spacing causes characters to spread farther apart, while negative values of letter-spacing bring characters closer together.


## Values

<dl>
<dt>normal</dt>
<dd>The normal letter spacing for the current font. Unlike a value of 0, this keyword allows the user agent to alter the space between characters in order to justify text.</dd>

<dt><length></dt>
<dd>Specifies extra inter-character space in addition to the default space between characters. Values may be negative, but there may be implementation-specific limits. User agents may not further increase or decrease the inter-character space in order to justify text.</dd>
</dl>

## Examples

```
letter-spacing="normal"
letter-spacing="0.4em"
letter-spacing="1em"
letter-spacing="-0.05em"
letter-spacing="6px"
```