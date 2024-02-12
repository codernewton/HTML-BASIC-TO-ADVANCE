## Define an HTML Table
A table in HTML consists of table cells inside rows and columns.

#### `<table>` element

In HTML table, all table rows and columns write inside the `<table>` tag/element

**Example :**

```HTML
<table>  
  <tr>  
    <td>Emil</td>  
    <td>Tobias</td>  
    <td>Linus</td>  
  </tr>  
  <tr>  
    <td>16</td>  
    <td>14</td>  
    <td>10</td>  
  </tr>  
</table>
```

## Table Rows

Each table row starts with a `<tr>` and ends with a `</tr>` tag.

**Example :**

```HTML
  <tr>  
    <td>Emil</td>  
    <td>Tobias</td>  
    <td>Linus</td>  
  </tr> 
```

## Table Headers

Sometimes you want your cells to be table header cells. In those cases use the `<th>` tag instead of the `<td>` tag.

**Example :**

```HTML
<table>  
  <tr>  
    <th>Person 1</th>  
    <th>Person 2</th>  
    <th>Person 3</th>  
  </tr>  
  <tr>  
    <td>Emil</td>  
    <td>Tobias</td>  
    <td>Linus</td>  
  </tr>  
  <tr>  
    <td>16</td>  
    <td>14</td>  
    <td>10</td>  
  </tr>  
</table>
```

## Table Cells

Each table cell is defined by a `<td>` and a `</td>` tag.  ___`td` stands for table data.___ Everything between `<td>` and `</td>` are the content of the table cell.

**Example :**

```HTML
<table>  
  <tr>  
    <td>Emil</td>  
    <td>Tobias</td>  
    <td>Linus</td>  
  </tr>  
</table>
```

# `<caption>` Tag

The `<caption>` tag defines a table caption. The `<caption>` tag must be inserted immediately after the `<table>` element.

### Example

Position table captions (with CSS) :

```HTML
<table>  
  <caption style="text-align:right">My savings</caption>  
  <tr>  
    <th>Month</th>  
    <th>Savings</th>  
  </tr>  
  <tr>  
    <td>January</td>  
    <td>$100</td>  
  </tr>  
</table
```

## Table Colgroup

The `<colgroup>` element is used to style specific columns of a table. The `<colgroup>` element should be used as a container for the column specifications. Each group is specified with a `<col>` element. The `span` attribute specifies how many columns that get the style. The `style` attribute specifies the style to give the columns.

### `<colgroup>` Tag 

The `<colgroup>` tag specifies a group of one or more columns in a table for formatting.

The `<colgroup>` tag must be a child of a `<table>` element, after any `<caption>` elements and before any `<thead>`, `<tbody>`, `<tfoot>`, and `<tr>` elements.

## Attributes

| Attribute | Value | Description |
| ---- | ---- | ---- |
| span | _number_ | Specifies the number of columns a column group should span |
|  |  |  |

### `<col>` tag

The `<col>` tag specifies column properties for each column within a `<colgroup>` element.
The `<col>` tag is useful for applying styles to entire columns, instead of repeating the styles for each cell, for each row.


Example :

```HTML
<table>  
  <colgroup>  
    <col span="2" style="background-color:red">  
    <col style="background-color:yellow">  
  </colgroup>  
  <tr>  
    <th>ISBN</th>  
    <th>Title</th>  
    <th>Price</th>  
  </tr>  
  <tr>  
    <td>3476896</td>  
    <td>My first HTML</td>  
    <td>$53</td>  
  </tr>  
</table>
```


### Empty Colgroup

If you want to style columns in the middle of a table, insert a "empty" `<col>` element (with no styles) for the columns before :

***Example :***

```HTML
<table style="width: 100%;">
<colgroup>
  <col span="3">
  <col span="2" style="background-color: pink">
</colgroup>
<tr>
<th>MON</th>
<th>TUE</th>
<th>WED</th>
<th>THU</th>
<th>FRI</th>
<th>SAT</th>
<th>SUN</th>
</tr>
<tr>
<td>1</td>
<td>2</td>
<td>3</td>
<td>4</td>
<td>5</td>
<td>6</td>
<td>7</td>
</tr>
<tr>
<td>8</td>
<td>9</td>
<td>10</td>
<td>11</td>
<td>12</td>
<td>13</td>
<td>14</td>
</tr>
<tr>
<td>15</td>
<td>16</td>
<td>17</td>
<td>18</td>
<td>19</td>
<td>20</td>
<td>21</td>
</tr>
<tr>
<td>22</td>
<td>23</td>
<td>24</td>
<td>25</td>
<td>26</td>
<td>27</td>
<td>28</td>
</tr>
</table>
```

### Hide Columns

You can hide columns with the `visibility: collapse` property :

```HTML
<colgroup>
    <col span="2">
    <col span="3" style="visibility: collapse">
  </colgroup>
<tr>
```
### The `<thead>`, `<tbody>`, and `<tfoot>` elements

The `<thead>` tag is used to group header content in an HTML table. The `<tbody>` tag is used to group the body content in an HTML table. The `<tfoot>` tag is used to group footer content in an HTML table.

Example :

```HTML
<table>  
  <thead>  
    <tr>  
      <th>Month</th>  
      <th>Savings</th>  
    </tr>  
  </thead>  
  <tbody>  
    <tr>  
      <td>January</td>  
      <td>$100</td>  
    </tr>  
    <tr>  
      <td>February</td>  
      <td>$80</td>  
    </tr>  
  </tbody>  
  <tfoot>  
    <tr>  
      <td>Sum</td>  
      <td>$180</td>  
    </tr>  
  </tfoot>  
</table>
```

# Table Style

### HTML Table Borders

HTML tables can have borders of different styles and shapes.

To add a border, use `border` property on `table`, `th`, and `td` elements :

Example :

```CSS
table, th, td { 
 border: 1px solid black;
}
```

## Collapsed Table Borders

To avoid having double borders like in the example above, set the CSS `border-collapse` property to `collapse`. This will make the borders collapse into a single border.

|  |  |  |  |  |  |
| ---- | ---- | ---- | ---- | ---- | ---- |
|  |  |  |  |  |  |
|  |  |  |  |  |  |
|  |  |  |  |  |  |
Example :

```CSS
 table, th, td {  
  border: 1px solid black;  
  border-collapse: collapse;
 }
```

##  Table Sizes

HTML tables can have different sizes for each column, row or the entire table. Use the `style`attribute with the `width` or `height` properties to specify the size of a table, row or column.

### Table column Width

To set the width of a table, add the `style` attribute to the `<table>` element:

```HTML
<table style="width:100%">  
  <tr>  
    <th>Firstname</th>  
    <th>Lastname</th>  
    <th>Age</th>  
  </tr>  
  <tr>  
    <td>Jill</td>  
    <td>Smith</td>  
    <td>50</td>  
  </tr>    
</table>
```

To set the size of a specific column, add the `style` attribute on a `<th>` or `<td>` element :

```HTML
<table style="width:100%">  
  <tr>  
    <th style="width:70%">Firstname</th>  
    <th>Lastname</th>  
    <th>Age</th>  
  </tr>  
  <tr>  
    <td>Jill</td>  
    <td>Smith</td>  
    <td>50</td>  
  </tr>    
</table>
```

### Table Row Height

To set the height of a specific row, add the `style` attribute on a table row element :

```HTML
<table style="width:100%">  
  <tr>  
    <th>Firstname</th>  
    <th>Lastname</th>  
    <th>Age</th>  
  </tr>  
  <tr style="height:200px">  
    <td>Jill</td>  
    <td>Smith</td>  
    <td>50</td>  
  </tr>  
  <tr>  
    <td>Eve</td>  
    <td>Jackson</td>  
    <td>94</td>  
  </tr>  
</table>
```

### Table Headers

HTML tables can have headers for each column or row, or for many columns/rows. Table headers are defined with `th` elements. Each `th` element represents a table cell.

```HTML
<table>  
  <tr>  
    <th>Firstname</th>  
    <th>Lastname</th>  
    <th>Age</th>  
  </tr>  
  <tr>  
    <td>Jill</td>  
    <td>Smith</td>  
    <td>50</td>  
  </tr>  
  <tr>  
    <td>Eve</td>  
    <td>Jackson</td>  
    <td>94</td>  
  </tr>  
</table>
```

### Vertical Table Headers

To use the first column as table headers, define the first cell in each row as a `<th>` element:

```HTML
<table>  
  <tr>  
    <th>Firstname</th>  
    <td>Jill</td>  
    <td>Eve</td>  
  </tr>  
  <tr>  
    <th>Lastname</th>  
    <td>Smith</td>  
    <td>Jackson</td>  
  </tr>  
  <tr>  
    <th>Age</th>  
    <td>94</td>  
    <td>50</td>  
  </tr>  
</table>
```

## Header for Multiple Columns

You can have a header that spans over two or more columns. To do this, use the `colspan` attribute on the `<th>` element :

```HTML
<table>  
  <tr>  
    <th colspan="2">Name</th>  
    <th>Age</th>  
  </tr>  
  <tr>  
    <td>Jill</td>  
    <td>Smith</td>  
    <td>50</td>  
  </tr>  
  <tr>  
    <td>Eve</td>  
    <td>Jackson</td>  
    <td>94</td>  
  </tr>  
</table>
```

### HTML Table - Cell Padding

Cell padding is the space between the cell edges and the cell content. By default the padding is set to 0. To add padding on table cells, use the CSS `padding` property :

```CSS
th, td {  
 padding: 15px;
}
```


### HTML Table - Cell Spacing

Cell spacing is the space between each cell. By default the space is set to 2 pixels. To change the space between table cells, use the CSS `border-spacing` property on the `table` element :

```CSS
table {  border-spacing: 30px;}
```

### Table Colspan & Rowspan

HTML tables can have cells that span over multiple rows and/or columns. 

To make a cell span over multiple columns, use the `colspan` attribute :

```HTML
<table style="width:100%">
  <tr>
    <th colspan="2">Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>43</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>57</td>
  </tr>
</table>
```

To make a cell span over multiple rows, use the `rowspan` attribute :

```HTML
<table>  
  <tr>  
    <th>Name</th>  
    <td>Jill</td>  
  </tr>  
  <tr>  
    <th rowspan="2">Phone</th>  
    <td>555-1234</td>  
  </tr>  
  <tr>  
    <td>555-8745</td>  
</tr>  
</table>
```

## Nested Table

A table inside another table:

**Example :**

```HTML
<table>  
  <tr>  
    <td>Cell</td>  
    <td>Nested Table  
      <table>  
        <tr>  
          <td>Cell 1</td>  
        </tr>  
        <tr>  
          <td>Cell 2</td>  
        </tr>  
        <tr>  
          <td>Cell 3</td>  
        </tr>  
        <tr>  
          <td>Cell 4</td>  
        </tr>  
      </table>  
    </td>  
  </tr>  
</table>
```





