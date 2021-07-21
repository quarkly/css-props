# background-clip

The background-clip CSS property sets whether an element's background extends underneath its border box, padding box, or content box.


## Values

<dl>
<dt>border-box</dt>
<dd>The background extends to the outside edge of the border (but underneath the border in z-ordering).</dd>

<dt>padding-box</dt>
<dd>The background extends to the outside edge of the padding. No background is drawn beneath the border.</dd>

<dt>content-box</dt>
<dd>The background is painted within (clipped to) the content box.</dd>

<dt>text </dt>
<dd>The background is painted within (clipped to) the foreground text.</dd>
</dl>

## Examples

```
background-clip="border-box"
background-clip="padding-box"
background-clip="content-box"
background-clip="text"
```