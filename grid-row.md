# grid-row

The grid-row CSS shorthand property specifies a grid item’s size and location within the grid row by contributing a line, a span, or nothing (automatic) to its grid placement, thereby specifying the inline-start and inline-end edge of its grid area.


## Values

<dl>
<dt>auto</dt>
<dd>Is a keyword indicating that the property contributes nothing to the grid item’s placement, indicating auto-placement, an automatic span, or a default span of 1.</dd>

<dt><custom-ident></dt>
<dd>If there is a named line with the name '<custom-ident>-start'/'<custom-ident>-end', it contributes the first such line to the grid item’s placement.
Note: Named grid areas automatically generate implicit named lines of this form, so specifying grid-column: foo; will choose the start/end edge of that named grid area (unless another line named foo-start/foo-end was explicitly specified before it).</dd>

<dd>Otherwise, this is treated as if the integer 1 had been specified along with the <custom-ident>.</dd>

<dt><integer> && <custom-ident>?</dt>
<dd>Contributes the nth grid line to the grid item’s placement. If a negative integer is given, it instead counts in reverse, starting from the end edge of the explicit grid.
If a name is given as a <custom-ident>, only lines with that name are counted. If not enough lines with that name exist, all implicit grid lines are assumed to have that name for the purpose of finding this position.</dd>

<dd>An <integer> value of 0 is invalid.</dd>

<dt>span && [ <integer> || <custom-ident> ]</dt>
<dd>Contributes a grid span to the grid item’s placement such that the corresponding edge of the grid item’s grid area is n lines from the opposite edge.
If a name is given as a <custom-ident>, only lines with that name are counted. If not enough lines with that name exist, all implicit grid lines on the side of the explicit grid corresponding to the search direction are assumed to have that name for the purpose of counting this span.</dd>

<dd>If the <integer> is omitted, it defaults to 1. Negative integers or 0 are invalid.</dd>
</dl>


## Examples

```
grid-row="auto"
grid-row="auto / auto"
grid-row="somegridarea"
grid-row="somegridarea / someothergridarea"
```