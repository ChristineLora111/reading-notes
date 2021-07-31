## Read 06: Tables, Functions, Methods, and Objects:
[Go back to Reading Notes home](README.md)

<b><h3>Chapter 6: “Tables” (pp.126-145)</h3></b>

Tables represent a grid format. Grids references information on two axes. Each block in the grid is referred to as a table cell. In HTML a table is written
out row by row. 

< table >
- used to create a table. Contents of the table are written out row by row.

< tr >
- stands for the table row. It's the start of each row. It's then followed by < td > elements. One for each cell in that row.

< td >
- represents each cell of a table. 

< th ><br/>
- stands for TABLE HEADER
- it's used just like the < td > element, but it's purpose is to represent the heading for either a column or a row. 
- even if a cell has no content, its still important to use a < td > or < th > to represent the presence of an empty cell, or else it won't render correctly.

< td colspan="2" > Content < /td >
- this means the cell will run across two columns.

< td rowspan="3" > Content < /td >
- this shows how many rows a cell should span down the table.

For long tables, you can split the table into a < thead >, < tbody > and < tfoot >.


<b><h3>Chapter 3: “Functions, Methods, and Objects” (pp.106-144)</h3></b>

Functions:
- They allow you to group a set of related statements together that represent a single task.
- They can take parameters, which is the information needed to do their job) and may return a value.

Objects:
- series of variables and functions that represent something from the world around you
- inside an object, variables are known as PROPERTIES of the object. Functions are known as methods of the objects.

Web browsers implement objects that represent both. the browser window and the document loaded into the browser window.

Arrays and objects can be used to create complex data sets and both can contain the other.

JavaScript also has a couple built in objects like string, number, math and date. Their properties and methods offer functionality that help you write scripts.


