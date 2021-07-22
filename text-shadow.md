# text-shadow

The text-shadow CSS property adds shadows to text. It accepts a comma-separated list of shadows to be applied to the text and any of its decorations. Each shadow is described by some combination of X and Y offsets from the element, blur radius, and color.

## Values

<dl>
<dt>&lt;color&gt;</dt>
<dd>Optional. The color of the shadow. It can be specified either before or after the offset values. If unspecified, the color's value is left up to the user agent, so when consistency across browsers is desired you should define it explicitly.</dd>
<dt>&lt;offset-x&gt; &lt;offset-y&gt;</dt>
<dd>Required. These &lt;length&gt; values specify the shadow's distance from the text. &lt;offset-x&gt; specifies the horizontal distance; a negative value places the shadow to the left of the text. &lt;offset-y&gt; specifies the vertical distance; a negative value places the shadow above the text. If both values are 0, the shadow is placed directly behind the text, although it may be partly visible due to the effect of &lt;blur-radius&gt;.</dd>
<dt>&lt;blur-radius&gt;</dt>
<dd>Optional. This is a &lt;length&gt; value. The higher the value, the bigger the blur; the shadow becomes wider and lighter. If not specified, it defaults to 0.</dd>
</dl>

## Examples

```
text-shadow="red 0 -2px"
text-shadow="1px 1px 2px black, 0 0 1em blue, 0 0 0.2em blue"
```
