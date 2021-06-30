## font-weight

The font-weight CSS property sets the weight (or boldness) of the font. The weights available depend on the font-family that is currently set.


## Values

normal
Normal font weight. Same as 400.

bold
Bold font weight. Same as 700.

lighter
One relative font weight lighter than the parent element. Note that only four font weights are considered for relative weight calculation; see the Meaning of relative weights section below.

bolder
One relative font weight heavier than the parent element. Note that only four font weights are considered for relative weight calculation; see the Meaning of relative weights section below.

<number>
A <number> value between 1 and 1000, inclusive. Higher numbers represent weights that are bolder than (or as bold as) lower numbers. Certain commonly used values correspond to common weight names, as described in the Common weight name mapping section below.

In earlier versions of the font-weight specification, the property accepts only keyword values and the numeric values 100, 200, 300, 400, 500, 600, 700, 800, and 900; non-variable fonts can only really make use of these set values, although fine-grained values (e.g. 451) will be translated to one of these values for non-variable fonts using the Fallback weights system.

CSS Fonts Level 4 extends the syntax to accept any number between 1 and 1000 and introduces Variable fonts, which can make use of this much finer-grained range of font weights.

## Examples

font-weight: 500;
font-weight: normal;
