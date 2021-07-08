# shadow-blur-radius

This is a third value. The larger this value, the bigger the blur, so the shadow becomes bigger and lighter.


## Values

<dl>
<dd>This is a third <length> value. The larger this value, the bigger the blur, so the shadow becomes bigger and lighter. Negative values are not allowed. If not specified, it will be 0 (the shadow's edge is sharp). The specification does not include an exact algorithm for how the blur radius should be calculated, however, it does elaborate as follows:</dd>

<dd>…for a long, straight shadow edge, this should create a color transition the length of the blur distance that is perpendicular to and centered on the shadow’s edge, and that ranges from the full shadow color at the radius endpoint inside the shadow to fully transparent at the endpoint outside it.</dd>
</dl>

## Examples

```
"20px"
"10px"
```