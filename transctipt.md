

Hello, my name is Maria Larchenko.  
**(Slide 2)**
CSS Grid is a two dimentional layout system. Unlike flexbox, which is largerly a 1-dimentional system, CSS grid can handle both row
and column.
 The grid give you a flexible way to change the position of element with only CSS without change to the HTML.   
**(Slide 3)**  
At that moment grid support in the latest version of all majior browser.  
**(Slide 4)**
For example I am create the simple layout with header, main, aside, footer sections . 
there is div like container, and 4 div inside like items. 
To creat a grid you have to define property **display: grid** on the container element. 
The child of the container becomes grid-items.
Now it is  look like  this.  
**(Slide 5)**
Next define rows and columns. You can do it using the property **grid-template-columns 
and grid-template-rows**. 
These property allow to define size and number of the columns and rows. The size can be in px,% and other. Using px you creat
fixing-size element. 
To create space between items you can use **grid-column-gap** or set space between columns,  **grid-row-gap** for set space between 
rows .
Or shorthand **grid-gap**.
To do grid responsive using **fraction(fr)** units. 
The  fraction unit, representing a fraction of the available space in the container. 
In this  case no matter how wide container get, items grow and shrink in the proportion.
It may turn out that all the items will have the same size.
This syntaxis where you have some repeating size can be write with **repeat ()** function,where first value it is number of 
repeating items, the second  is  size.
If you need that some part have fixed size you can mix px and fr. 
In this case fr unit share the space which left after fixed size units.
The function **minmax()** allow you creat flexible units where the first value set minimum size second - maximum size.  
**(Slide 6)**
You also can set properties for the Children
Set position of items in grid can with property **grid-column-start
Grid-column-end
Grid-row-start
Grid-row-end**
The start and end position you can use this property. Or use shorthand **grid-row, grid-column**. In this property the first value is
the start position of grid-item. The second is the end position.     
**(Slide 7)**
Another way to set position is to use **grid-template-areas**.
The grid -template-areas allows you to create each named grid-area within our grid. You simply write our grid exactly how it
should appear in the browser. Each line represents a row, and each cell within the string represents a column.
You can repeat cell names to create a grid area that takes up multiple cells. This property is set on the container.
On the items set the property **grid-area**.
Grid-area gives an item a name so that it can be referenced by a template created with the grid-template-areas property.   
**(Slide 8)**
**Justify-self** aligns a grid item inside a cell along the row axis.
It have 4 values: start, end, center, stretch(this is the default).
**Align-self** aligns a grid item inside a cell along the column axis. Also have 4 values: start, end, center, stretch(this is the default).
To set alignment for all the items in a grid, this behavior can also be set on the grid container via the justify-items property.
**(Slide 9)**
## Thank you for attention!

