## table-layout

The table-layout CSS property sets the algorithm used to lay out <table> cells, rows, and columns.


## Values

auto
By default, most browsers use an automatic table layout algorithm. The widths of the table and its cells are adjusted to fit the content.

fixed
Table and column widths are set by the widths of table and col elements or by the width of the first row of cells. Cells in subsequent rows do not affect column widths.

Under the "fixed" layout method, the entire table can be rendered once the first table row has been downloaded and analyzed. This can speed up rendering time over the "automatic" layout method, but subsequent cell content might not fit in the column widths provided. Cells use the overflow property to determine whether to clip any overflowing content, but only if the table has a known width; otherwise, they won't overflow the cells.

## Examples

table-layout: auto;
table-layout: fixed;
table-layout: inherit;