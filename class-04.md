## Read 04: HTML/CSS Book - Links & Layouts
[Go back to Reading Notes home](README.md)

<b>Chapter 4: Ch.4 “Links” (pp.74-93)</b>
- Uses the < a > element.
- "href" attribute (EX: < a href = "URL LINK" >Text User Clicks On < / a >
- Preferably, you should put text that explain where the visitor will be taken
- URL stands for Uniform Resource Locator

Email links:
- To create a link that starts up the users email program and addresses an an email to a specific alias.
- < a href = "mail to:example@email.com" > Email User < / a >

Opening Links to a New Window:
- Use target attribute on the opening < a > tag.
- Value of attribute should be _ blank
- Always good to inform users that the link will open a new window
- < a href = "URL" target = "_ blank" > 

Linking to a Specific Part of the Same Page:
- Before linking to a specific part of a page, you need to identify the point in the page that the link will go to. This is
done through the "id" attribute
- < h1 id = "top" > Top Of Page< / h >
- The URL that's at the bottom to get to that ^^ : < a href "#top" >Top< / a >
< br/> 

<b>Chapter 15: “Layout” (pp.358-404)</b>
- CSS treats each HTML element as if its in its own box. Box will either be block-level or inline box.

Block-Level boxes:
- Start on a new line and acts as the main building blocks of any layout
- EX: < h1 >, < p >, < ul >, < li >

Inline boxes:
- Flow between surrounding text
- < img > < b >, < i >

Can be customizable by setting the width of the boxes, sometimes height.
- borders, margins, padding and background colors

Browsers can display pages in normal flow, unless you specifically specify absolute, fixed or relative positioning.
- The float property moves content to the left or right of the page.
- Can be used to create multi-column layouts
- Designers preferable keep pages within 960-1000 pixels wide.
- They indicate wha the site is about within the top 600 pixels to show and demonstrate its relevance without scrolling.
- Grids help create professional and flexible designs.
- CSS frameworks provide rules for common tasks.
- You can include multiple CSS files in one page.

## Read 04: JavaScript & JQuery Book - Functions, Methods, and Objects

Functions:
- Functions allow you to group a set of related statements together that represent a single task. (Function = you're functioning by doing something)
- Can take parameters (The information required to do the job, to deploy the action) and the result could be returning a value

Object:
- Series of variables and functions that represent something from the world around you
- In an open, variables are known as properties of the object. Functions are known as methods of the object.

Web browsers implement objects that represent both the browser window and the document loaded into the browser window.l

Javascript has a couple built in objects. Their properties and methods offer functionality that help you write scripts:
- String
- Number
- Math 
- Date

Arrays and objects are used to create complex data sets and both can contain the other.
