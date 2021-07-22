# filter

The filter CSS property applies graphical effects like blur or color shift to an element. Filters are commonly used to adjust the rendering of images, backgrounds, and borders.

Included in the CSS standard are several functions that achieve predefined effects. You can also reference an SVG filter with a URL to an SVG filter element.

## Values

<dl>
<dt>drop-shadow()</dt>
<dd>The drop-shadow() function applies a drop shadow effect to the input image. A drop shadow is effectively a blurred, offset version of the input image's alpha mask drawn in a particular color, composited below the image. The function accepts a parameter of type &lt;shadow&gt; (defined in CSS3 Backgrounds), with the exception that the inset keyword and spread parameter are not allowed. This function is similar to the more established box-shadow property; the difference is that with filters, some browsers provide hardware acceleration for better performance. The parameters of the &lt;shadow&gt; parameter are as follows:</dd>
<dt>&lt;offset-x&gt; &lt;offset-y&gt; (required)</dt>
<dd>These are two &lt;length&gt; values to set the shadow offset. &lt;offset-x&gt; specifies the horizontal distance. Negative values place the shadow to the left of the element. &lt;offset-y&gt; specifies the vertical distance. Negative values place the shadow above the element. See &lt;length&gt; for possible units.
If both values are 0, the shadow is placed behind the element (and may generate a blur effect if &lt;blur-radius&gt; and/or &lt;spread-radius&gt; is set).</dd>
<dt>&lt;blur-radius&gt; (optional)</dt>
<dd>This is a third &lt;length&gt; value. The larger this value, the bigger the blur, so the shadow becomes bigger and lighter. Negative values are not allowed. If not specified, it will be 0 (the shadow's edge is sharp).</dd>
<dt>&lt;color&gt; (optional)</dt>
<dd>See &lt;color&gt; values for possible keywords and notations. If not specified, the color used depends on the browser - it is usually the value of the &lt;color&gt; property, but note that Safari currently paints a transparent shadow in this case.</dd>
</dl>

## Examples

```
filter="drop-shadow(16px 16px 10px black)"
filter="blur(5px)"
filter="brightness(0.4)"
filter="contrast(200%)"
```
