# Module 7: Tables

In this module, we will dive into tables in HTML. Tables are used to display data in rows and columns, making it easier to organize and present information. We'll cover creating tables, table rows and cells, table headers, merging cells, and adding captions and summaries. Let's get started!

### 7.1: Creating Tables (`<table>`)
To create a table in HTML, we use the `<table>` element. It acts as the container for the entire table structure. Here's an example of a basic table:

```html
<table>
  <!-- table content goes here -->
</table>
```

Inside the `<table>` element, we'll add the necessary components to build the table.

### 7.2: Table Rows (`<tr>`) and Cells (`<td>`)
Tables are made up of rows and cells. Each row is represented by the `<tr>` element, and each cell within the row is represented by the `<td>` element. Here's an example of a table with three rows and three cells:

```html
<table>
  <tr>
    <td>Row 1, Cell 1</td>
    <td>Row 1, Cell 2</td>
    <td>Row 1, Cell 3</td>
  </tr>
  <tr>
    <td>Row 2, Cell 1</td>
    <td>Row 2, Cell 2</td>
    <td>Row 2, Cell 3</td>
  </tr>
  <tr>
    <td>Row 3, Cell 1</td>
    <td>Row 3, Cell 2</td>
    <td>Row 3, Cell 3</td>
  </tr>
</table>
```

In this example, we have three rows (`<tr>`) and three cells (`<td>`) in each row. You can add content within the cells, such as text, images, or other HTML elements.

### 7.3: Table Headers (`<th>`)
Tables often have headers to label the columns or provide additional information. The `<th>` element is used to define table headers. By default, table headers are bold and centered. Here's an example:

```html
<table>
  <tr>
    <th>Column 1</th>
    <th>Column 2</th>
    <th>Column 3</th>
  </tr>
  <!-- table rows and cells go here -->
</table>
```

In this example, we've added `<th>` elements within the first row (`<tr>`) to define the column headers.

### 7.4: Merging Cells (colspan and rowspan)
HTML allows you to merge cells in a table using the `colspan` and `rowspan` attributes. These attributes define how many columns or rows a cell should span. Here's an example:

```html
<table>
  <tr>
    <td rowspan="2">Merged Cell</td>
    <td>Row 1, Cell 2</td>
    <td>Row 1, Cell 3</td>
  </tr>
  <tr>
    <td>Row 2, Cell 2</td>
    <td>Row 2, Cell 3</td>
  </tr>
</table>
```

In this example, the first cell in the first row (`<td rowspan="2">Merged Cell</td>`) spans two rows. This creates a merged cell that occupies the space of two regular cells.

### 7.5: Adding Captions and Summaries
Tables can have captions and summaries to provide additional context and description. The `<caption>` element is used to add a caption to the table, and the `<summary>` element provides a summary of the table's content. Here's an example:

```html
<table>
  <caption>This is a table caption</caption>
  <summary>This table displays sales data for the past month.</summary>
  <tr>
    <!-- table header and cells go here -->
  </tr>
  <!-- additional rows go here -->
</table>
```

In this example, we've added a `<caption>` element to provide a title for the table and a `<summary>` element to summarize its content.

### 7.6: Closing Thoughts
In Module 7, we've learned how to create tables, define table rows and cells, add table headers, merge cells, and include captions and summaries. Practice creating different types of tables and experiment with different attributes and styles. 

In the next module, we will explore forms in HTML.

<br>

<p align="left"><a href="https://github.com/vennby/ChatGPT-University/blob/main/HTML/Module%206.md"><< Previous</a></p>
<p align="center"><a href="https://github.com/vennby/ChatGPT-University/blob/main/HTML/Handout.md">Handout</p>
<p align="right"><a href="https://github.com/vennby/ChatGPT-University/blob/main/HTML/Module%208.md">Next >></p>
