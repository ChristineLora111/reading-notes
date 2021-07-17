## Read 03: HTML Lists, Control Flow with JS, and the CSS Box Model:
[Go back to Reading Notes home](README.md)

### <b>Chapter 3: “Lists” (pp.62-73) Summary:</b>
There are 3 different types of lists in HTML
- Ordered lists
- Unordered lists
- Definition lists
- Nested lists: putting a second list inside an < li > element to create a sub list or nested list.
< ol >: Ordered list with numbers
< li >: Stands for list item. Each item in the list is placed between this.
< ul >: Unordered list that's bullet pointed.
< dl >: Definition list consists of a series of terms and their definitions. It's usually paired with the < dd > and < dt > element in it.
< dt >: This contains the term being defined (definition term)
< dd >: This is used to contain the definition

### <b>Chapter 13: “Boxes” (pp.300-329) Summary:</b>
Box Dimensions: width and height
- Popular way to specify the size of a box are pixels, percentages or ems. Pixels are the most used
- Percentages: Size of the box is relative to the size of the browser window
- Ems: The size of the box is based on the size of text within it.

Limiting Width: min-width, max-width
- Some page designs expand and shrink to fit the size of the users screen.
- min-width: It specifies the smallest size a box can be displayed at when the browser window is narrow.
- max-width: Property indicates the maximum width a box can stretch to when the browser window is wide.
- There are helpful properties to ensure that the contents of pages are legible (mainly for smaller screens of handheld devices).
EX: You use max-width property to ensure that lines of text do not appear too wide within a big browser window and you can use the min-width property
to make sure that they do not appear too narrow. 

Limiting Height: min-height, max-height
- When you limit the width of a box on a page, you may also want to limit the width of a box on a page, you may also want to limit the height of it. This
is achieved using the min-height and max height properties. 

Overflowing Content: overflow
- The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have two values:
1) hidden: This property simple hides any extra content that does not fit in the box.
2) scroll: This property adds a scrollbar to the box so that users can scroll to see the missing content.

Border, Margin & Padding:
- Every box has 3 available properties that can be adjusted to control it appearance:
1) Border: Every box has a border (even if it is not visible or is specified to be 0 pixels wide) The border separates the edge of one box from another.
2) Margin: Margins sit outside the edge of the border. You can set the width of a marin to create a gap between the borders of two adjacent boxes.
3) Padding: Padding is the space between the border of a box and any content contained within it. Adding padding can increase the readability of its contents.

If you specify a width for a box, then the borders, margin and padding are added to it's width and height.

White Space & Vertical Margin:
- The padding and margin properties are very helpful in adding space between various items on the page.
- Designers refer to the space between items on a page as white space.
- Imagine you had a border around a box. You wouldn't want the text to touch the border. 

Border Width: border-width
- The border-width property is used to control the width of a border. The value of this property can either be given 
in pixels or using one of the follow values:
- thin
- medium
- thick
(You can't use percentages with this property)

You can control the individual size of borders using four separate properties:
- border-top-width
- border-right-width
- border-bottom-width
- border-left-width
You can specify different widths for the four border values in one property, like so:
- border-width: 2 px, 1 px, 1 px, 2 px

Border Style: border-style
- Controlling the style of a border using the border-style property. This property can take the following value:

solid: a single sold line
dotted: a series of square dots
dashed: a series of short lines
double: two solid lines
groove: appears to be carved into the page
ridge: appears to stick out from the page
inset: appears embedded into the page
outset: looks like it is coming out of the screen
hidden/none: no border is shown

This can be individually change the style of different borders using:
- border-top-style <br />
- border-left-style <br />
- border-right-style <br />
- border-bottom-style <br />

Border Color: border-color
- You can specify the color of a border using either RCB values, hex codes or CSS color names <br />

<b>You can also individually control the colors of the borders on different sides of a box using:</b>
border-top-color <br />
border-right-color <br />
border-bottom-color <br />
border-left-color <br />

The shorthand to control all four border colors in the one property:

border-color: darkcyan <br />
deeppink darkcyan <br />
deeppink; <br />

Shorthand: border
- Border property allows you to specify the width, style, and color of a border in one property (which needs to be in that specific order)

- Padding: padding
- Margin: margin
- Centering Content
- IE6 Box Model
- Change Inline/Block: display
- Hiding Boxes: visibility
- CSS3: Border Images: border-image
- CSS3: Box Shadows: box-shadow
- CSS3: Rounded Corners: border-radius
- CSS3: Elliptical Shapes: border-radius


### <b>Chapter 2: “Basic JavaScript Instructions” (pp.70-73)</b><br />
Script = Series of statements.
- They contain exact instructions that need to be done
Variables = used to store temporary information used in the script
Arrays = Special variables that store more than one piece of related information

JavaScript distinguishes between numbers, strings and Boolean values
  Numbers: 0-9 <br />
  Strings: text <br />
  Boolean: true or false<br />
Expressions: evaluate into a single value. They also rely on operators to calculate a value.
  
  
### <b>Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)</b><br />

 - Conditional statements = makes your code make decisions about what to do next
 - Comparison operators = used to compare two operands
 - If else statements = lets you run one set of code if a condition is true and another if its not true
 - Switch statements = lets you compare a value against possible outcomes. It also provides a default option if none work or match
 - Data types = Can be manipulated from one type to another
 - All values evaluate to truthy or falsy
 - Three types of loop:
  - for
  - while
  - do...while
  Each repeats a set of statements.















