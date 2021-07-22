# transition-duration

The transition-duration CSS property sets the length of time a transition animation should take to complete. By default, the value is 0s, meaning that no animation will occur.

## Values

<dl>
<dt>&lt;time&gt;</dt>
<dd>Is a &lt;time&gt; denoting the amount of time the transition from the old value of a property to the new value should take. A time of 0s indicates that no transition will happen, that is the switch between the two states will be instantaneous. A negative value for the time renders the declaration invalid.</dd>
</dl>

## Examples

```
transition-duration="6s"
transition-duration="120ms"
transition-duration="1s, 15s"
transition-duration="10s, 30s, 230ms"
```
