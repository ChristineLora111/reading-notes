## Read 12: Chart.js, Canvas:
[Go back to Reading Notes home](README.md)

<b><h3>Easily Create Stunning Animated Charts With Chart.js</h3></b>
https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/

- Charts tend to be more visually pleasing than tables. 
Benefits: They're easy to look at and they quickly convey data. They're just not easy to create. 

Chart.js:
- A JavaScript plugin that uses HTML5 canvas element to draw the graph onto the page.
- Helps you create bar charts, line charts, pie charts, etc more easily.

<h4>To Set Up:</h4>
- Download Chart.js
- Copy the Chart.min.js out of the unzipped folder and into the directory you'll be working in

<b><h3>Basic Usage of Canvas:</h3></b>
```
<canvas id="tutorial" width="150" height="150"></canvas>
```
The <canvas> element has only two attributes: width and height
  - They are both optional and can be set using DOM properties. 
  - When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. 
  - The element can be sized by using CSS, but during rendering, the image is scaled to git it's layout size. It will look distorted if the css sizing doesn't respect the ratio and the initial canvas.
  - If rendering looks distorted, you can try specifying the width and height attributes explicitly in the <canvas> attributes and not within the CSS.
  
id attribute:
  - It's not specific to the <canvas> element, but it is one of the global HTML attributes which can be applied to any HTML element (like class, for instance). It's always good to supply an id because this makes it much easier to idenity in a script.

The <canvas> element differs from an <img> tag in that, like for <video>, <audio>, or <picture> elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers. You should always provide fallback content to be displayed by those browsers.
  
<b><h3>Drawing Shapes with Canvas:</h3></b>
These are the shapes you can make:
  - Grid
  - Rectangles
  - Paths
  - A triangle
  - Moving the pen
  - Lines
  - Arcs
  - Bezier and quadratics curves
  - Quadratics bezier curves
  - Cubic bezier curves
  
<b><h3>Applying Styles and Colors:</h3></b>
 ```fillStyle = color```
```strokeStyle = color```
  
When you set the strokeStyle or fillStyle property, the new value becomes the default for all shapes being drawn from then on. For every shape you want in a different color, you'll need to reassign the fillStyle or strokeStyle property.
  
Transparency:
- Also draw semi-transparent (or translucent) shapes. This is done by either setting the globalAlpha property or by assigning a semi-transparent color to the stroke and/or fill style.

```globalAlpha = transparencyValue```
  
  
<b><h3>Drawing Text</h3></b>
two methods to render text:
```fillText(text, x, y [, maxWidth])```
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
```strokeText(text, x, y [, maxWidth])```
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

```font = value```
The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.
```textAlign = value```
Text alignment setting. Possible values: start, end, left, right or center. The default value is start.
```textBaseline = value```
Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.
```direction = value```
Directionality. Possible values: ltr, rtl, inherit. The default value is inherit.









