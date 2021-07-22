# transition-timing-function

The transition-timing-function CSS property sets how intermediate values are calculated for CSS properties being affected by a transition effect.

## Values

<dl>
<dt>&lt;easing-function&gt;</dt>
<dd>Each &lt;easing-function&gt; represents the easing function to link to the corresponding property to transition, as defined in transition-property.
The non-step keyword values (ease, linear, ease-in-out, etc.) each represent cubic Bézier curve with fixed four point values, with the cubic-bezier() function value allowing for a non-predefined value. The step timing functions divides the input time into a specified number of intervals that are equal in length. It is defined by a number of steps and a step position.</dd>
<dt>ease</dt>
<dd>Equal to cubic-bezier(0.25, 0.1, 0.25, 1.0), the default value, increases in velocity towards the middle of the transition, slowing back down at the end.</dd>
<dt>linear</dt>
<dd>Equal to cubic-bezier(0.0, 0.0, 1.0, 1.0), transitions at an even speed.</dd>
<dt>ease-in</dt>
<dd>Equal to cubic-bezier(0.42, 0, 1.0, 1.0), starts off slowly, with the transition speed increasing until complete.</dd>
<dt>ease-out</dt>
<dd>Equal to cubic-bezier(0, 0, 0.58, 1.0), starts transitioning quickly, slowing down the transition continues. •</dd>
<dt>ease-in-out</dt>
<dd>Equal to cubic-bezier(0.42, 0, 0.58, 1.0), starts transitioning slowly, speeds up, and then slows down again.</dd>
<dt>cubic-bezier(p1, p2, p3, p4)</dt>
<dd>An author defined cubic-Bezier curve, where the p1 and p3 values must be in the range of 0 to 1.</dd>
<dt>steps( n, &lt;jumpterm&gt;)</dt>
<dd>Displays the transition along n stops along the transition, displaying each stop for equal lengths of time. For example, if n is 5, there are 5 steps. Whether the transition holds temporarily at 0%, 20%, 40%, 60% and 80%, on the 20%, 40%, 60%, 80% and 100%, or makes 5 stops between the 0% and 100% along the transition, or makes 5 stops including the 0% and 100% marks (on the 0%, 25%, 50%, 75%, and 100%) depends on which of the following jump terms is used:</dd>
<dt>jump-start</dt>
<dd>Denotes a left-continuous function, so that the first jump happens when the transition begins;</dd>
<dt>jump-end</dt>
<dd>Denotes a right-continuous function, so that the last jump happens when the animation ends;</dd>
<dt>jump-none</dt>
<dd>There is no jump on either end. Instead, holding at both the 0% mark and the 100% mark, each for 1/n of the duration</dd>
<dt>jump-both</dt>
<dd>Includes pauses at both the 0% and 100% marks, effectively adding a step during the transition time.</dd>
<dt>start</dt>
<dd>Same as jump-start.</dd>
<dt>end</dt>
<dd>Same as jump-end.</dd>
<dt>step-start</dt>
<dd>Equal to steps(1, jump-start)</dd>
<dt>step-end</dt>
<dd>Equal to steps(1, jump-end)</dd>
</dl>

## Examples

```
transition-timing-function="ease-in"
transition-timing-function="ease-out"
transition-timing-function="ease-in-out"
transition-timing-function="linear"
```
