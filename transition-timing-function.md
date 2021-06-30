## transition-timing-function

The transition-timing-function CSS property sets how intermediate values are calculated for CSS properties being affected by a transition effect.


## Values

<easing-function>
Each <easing-function> represents the easing function to link to the corresponding property to transition, as defined in transition-property.
The non-step keyword values (ease, linear, ease-in-out, etc.) each represent cubic Bézier curve with fixed four point values, with the cubic-bezier() function value allowing for a non-predefined value. The step timing functions divides the input time into a specified number of intervals that are equal in length. It is defined by a number of steps and a step position.

ease
Equal to cubic-bezier(0.25, 0.1, 0.25, 1.0), the default value, increases in velocity towards the middle of the transition, slowing back down at the end.

linear
Equal to cubic-bezier(0.0, 0.0, 1.0, 1.0), transitions at an even speed.

ease-in
Equal to cubic-bezier(0.42, 0, 1.0, 1.0), starts off slowly, with the transition speed increasing until complete.

ease-out
Equal to cubic-bezier(0, 0, 0.58, 1.0), starts transitioning quickly, slowing down the transition continues. •

ease-in-out
Equal to cubic-bezier(0.42, 0, 0.58, 1.0), starts transitioning slowly, speeds up, and then slows down again.

cubic-bezier(p1, p2, p3, p4)
An author defined cubic-Bezier curve, where the p1 and p3 values must be in the range of 0 to 1.

steps( n, <jumpterm>)
Displays the transition along n stops along the transition, displaying each stop for equal lengths of time. For example, if n is 5,  there are 5 steps. Whether the transition holds temporarily at 0%, 20%, 40%, 60% and 80%, on the 20%, 40%, 60%, 80% and 100%, or makes 5 stops between the 0% and 100% along the transition, or makes 5 stops including the 0% and 100% marks (on the 0%, 25%, 50%, 75%, and 100%) depends on which of the following jump terms is used:

jump-start
Denotes a left-continuous function, so that the first jump happens when the transition begins;

jump-end
Denotes a right-continuous function, so that the last jump happens when the animation ends;

jump-none
There is no jump on either end. Instead, holding at both the 0% mark and the 100% mark, each for 1/n of the duration

jump-both
Includes pauses at both the 0% and 100% marks, effectively adding a step during the transition time.

start
Same as jump-start.

end
Same as jump-end.

step-start
Equal to steps(1, jump-start)

step-end
Equal to steps(1, jump-end)

## Examples

transition-timing-function: ease-in;
transition-timing-function: ease-out;
transition-timing-function: ease-in-out;
transition-timing-function: linear;