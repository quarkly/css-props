# flex

The flex CSS shorthand property sets how a flex item will grow or shrink to fit the space available in its flex container.

## Values

<dl>
<dt>initial</dt>
<dd>The item is sized according to its width and height properties. It shrinks to its minimum size to fit the container, but does not grow to absorb any extra free space in the flex container. This is equivalent to setting "flex: 0 1 auto".</dd>
<dt>auto</dt>
<dd>The item is sized according to its width and height properties, but grows to absorb any extra free space in the flex container, and shrinks to its minimum size to fit the container. This is equivalent to setting "flex: 1 1 auto".</dd>
<dt>none</dt>
<dd>The item is sized according to its width and height properties. It is fully inflexible: it neither shrinks nor grows in relation to the flex container. This is equivalent to setting "flex: 0 0 auto".</dd>
<dt>&lt;flex-grow&gt;</dt>
<dd>Defines the flex-grow of the flex item. Negative values are considered invalid. Defaults to 1 when omitted. (initial is 0)</dd>
<dt>&lt;flex-shrink&gt;</dt>
<dd>Defines the flex-shrink of the flex item. Negative values are considered invalid. Defaults to 1 when omitted. (initial is 1)</dd>
<dt>&lt;flex-basis&gt;</dt>
<dd>Defines the flex-basis of the flex item. A preferred size of 0 must have a unit to avoid being interpreted as a flexibility. Defaults to 0 when omitted. (initial is auto)</dd>
</dl>

## Examples

```
flex="auto"
flex="10em"
flex="30%"
flex="min-content"
```
