# table-layout

The table-layout CSS property sets the algorithm used to lay out &lt;table&gt; cells, rows, and columns.

## Values

<dl>
<dt>auto</dt>
<dd>By default, most browsers use an automatic table layout algorithm. The widths of the table and its cells are adjusted to fit the content.</dd>
<dt>fixed</dt>
<dd>Table and column widths are set by the widths of table and col elements or by the width of the first row of cells. Cells in subsequent rows do not affect column widths.</dd>
<dd>Under the "fixed" layout method, the entire table can be rendered once the first table row has been downloaded and analyzed. This can speed up rendering time over the "automatic" layout method, but subsequent cell content might not fit in the column widths provided. Cells use the overflow property to determine whether to clip any overflowing content, but only if the table has a known width; otherwise, they won't overflow the cells.</dd>
</dl>

## Examples

```
table-layout="auto"
table-layout="fixed"
table-layout="inherit"
```
