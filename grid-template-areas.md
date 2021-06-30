## grid-template-areas

The grid-template-areas CSS property specifies named grid areas, establishing the cells in the grid and assigning them names.


## Values

none
The grid container doesn’t define any named grid areas.

<string>+
A row is created for every separate string listed, and a column is created for each cell in the string. Multiple named cell tokens within and between rows create a single named grid area that spans the corresponding grid cells. Unless those cells form a rectangle, the declaration is invalid.

## Examples

grid-template-areas: none;
grid-template-areas: "a b";
grid-template-areas: "a b b"
                     "a c d";