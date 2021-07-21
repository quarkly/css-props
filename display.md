# display

The display CSS property sets whether an element is treated as a block or inline element and the layout used for its children, such as flow layout, grid or flex.

Formally, the display property sets an element's inner and outer display types. The outer type sets an element's participation in flow layout; the inner type sets the layout of children. Some values of display are fully defined in their own individual specifications; for example the detail of what happens when display: flex is declared is defined in the CSS Flexible Box Model specification. See the table at the end of this document for all of the individual specifications.


## Values

<dl>
<dt>block</dt>
<dd>The element generates a block element box, generating line breaks both before and after the element when in the normal flow.</dd>

<dt>inline</dt>
<dd>The element generates one or more inline element boxes that do not generate line breaks before or after themselves. In normal flow, the next element will be on the same line if there is space</dd>

<dt>flex</dt>
<dd>The element behaves like a block element and lays out its content according to the flexbox model.</dd>

<dt>grid</dt>
<dd>The element behaves like a block element and lays out its content according to the grid model.</dd>

<dt>flow</dt>
<dd>The element lays out its contents using flow layout (block-and-inline layout).
If its outer display type is inline or run-in, and it is participating in a block or inline formatting context, then it generates an inline box. Otherwise it generates a block container box.

Depending on the value of other properties (such as position, float, or overflow) and whether it is itself participating in a block or inline formatting context, it either establishes a new block formatting context (BFC) for its contents or integrates its contents into its parent formatting context.</dd>

<dt>flow-root</dt>
<dd>The element generates a block element box that establishes a new block formatting context, defining where the formatting root lies.</dd>

<dt>table</dt>
<dd>These elements behave like HTML <table> elements. It defines a block-level box.</dd>

<dt>contents</dt>
<dd>These elements don't produce a specific box by themselves. They are replaced by their pseudo-box and their child boxes. Please note that the CSS Display Level 3 spec defines how the contents value should affect "unusual elements" — elements that aren’t rendered purely by CSS box concepts such as replaced elements. See Appendix B: Effects of display: contents on Unusual Elements for more details.

Due to a bug in browsers this will currently remove the element from the accessibility tree — screen readers will not look at what's inside. See the Accessibility concerns section below for more details.</dd>

<dt>none</dt>
<dd>Turns off the display of an element so that it has no effect on layout (the document is rendered as though the element did not exist). All descendant elements also have their display turned off.
To have an element take up the space that it would normally take, but without actually rendering anything, use the visibility property instead.</dd>

<dt>inline-block</dt>
<dd>The element generates a block element box that will be flowed with surrounding content as if it were a single inline box (behaving much like a replaced element would).

It is equivalent to inline flow-root.</dd>

<dt>inline-table</dt>
<dd>The inline-table value does not have a direct mapping in HTML. It behaves like an HTML <table> element, but as an inline box, rather than a block-level box. Inside the table box is a block-level context.

It is equivalent to inline table.</dd>

<dt>inline-flex</dt>
<dd>The element behaves like an inline element and lays out its content according to the flexbox model.

It is equivalent to inline flex.</dd>

<dt>inline-grid</dt>
<dd>The element behaves like an inline element and lays out its content according to the grid model.</dd>
</dl>

## Examples

```
display="block"
display="inline"
display="inline-block"
display="flex"
```