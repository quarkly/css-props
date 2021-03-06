# flex-wrap

The flex-wrap CSS property sets whether flex items are forced onto one line or can wrap onto multiple lines. If wrapping is allowed, it sets the direction that lines are stacked.

## Values

<dl>
<dt>The following values are accepted:</dt>
<dt>nowrap</dt>
<dd>The flex items are laid out in a single line which may cause the flex container to overflow. The cross-start is either equivalent to start or before depending on the flex-direction value. This is the default value.</dd>
<dt>wrap</dt>
<dd>The flex items break into multiple lines. The cross-start is either equivalent to start or before depending flex-direction value and the cross-end is the opposite of the specified cross-start.</dd>
<dt>rap-reverse</dt>
<dd>Behaves the same as wrap but cross-start and cross-end are permuted.</dd>
</dl>

## Examples

```
flex-wrap="wrap"
flex-wrap="nowrap"
flex-wrap="wrap-reverse"
```
