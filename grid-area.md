# grid-area

The grid-area CSS shorthand property specifies a grid item’s size and location within a grid by contributing a line, a span, or nothing (automatic) to its grid placement, thereby specifying the edges of its grid area.

## Values

<dl>
<dt>auto</dt>
<dd>Is a keyword indicating that the property contributes nothing to the grid item’s placement, indicating auto-placement or a default span of 1.
<dt>&lt;custom-ident&gt;</dt>
<dd>If there is a named line with the name '&lt;custom-ident&gt;-start'/'&lt;custom-ident&gt;-end', it contributes the first such line to the grid item’s placement.
Note: Named grid areas automatically generate implicit named lines of this form, so specifying grid-area: foo; will choose the start/end edge of that named grid area (unless another line named foo-start/foo-end was explicitly specified before it).</dd>
<dd>Otherwise, this is treated as if the integer 1 had been specified along with the &lt;custom-ident&gt;.</dd>
<dt>&lt;integer&gt; && &lt;custom-ident&gt;?</dt>
<dd>Contributes the nth grid line to the grid item’s placement. If a negative integer is given, it instead counts in reverse, starting from the end edge of the explicit grid.
If a name is given as a &lt;custom-ident&gt;, only lines with that name are counted. If not enough lines with that name exist, all implicit grid lines are assumed to have that name for the purpose of finding this position.</dd>
<dd>An &lt;integer&gt; value of 0 is invalid.</dd>
<dt>span && [ &lt;integer&gt; || &lt;custom-ident&gt; ]</dt>
<dd>Contributes a grid span to the grid item’s placement such that the corresponding edge of the grid item’s grid area is n lines from the opposite edge.
If a name is given as a &lt;custom-ident&gt;, only lines with that name are counted. If not enough lines with that name exist, all implicit grid lines on the side of the explicit grid corresponding to the search direction are assumed to have that name for the purpose of counting this span.</dd>
<dd>If the &lt;integer&gt; is omitted, it defaults to 1. Negative integers or 0 are invalid.</dd>
</dl>

## Examples

```
grid-area="some-grid-area"
grid-area="some-grid-area / another-grid-area"
grid-area="4 some-grid-area"
grid-area="4 some-grid-area / 2 another-grid-area"
```
