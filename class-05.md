## Read 05: HTML/CSS Book - Images, Colors, Text
[Go back to Reading Notes home](README.md)

<b>Chapter 5: "Images” (pp.94-125)</b>
< img >: This is an empty element, which means there is no closing tag. It has to carry the following two attributes:
- src = Tells the browser where it can find the image file. Normally a URL pointing to an image on your own site.
- alt = Provides text description of the image which described the image if you can't see it.

title = you can use the title attibute with the < img > element to provide additional info about the image. 
height and width are also two attributes that can go with the < img > element.

Block element = Always appear on a new line

3 rules to remember when creating images for your website:
- Save images in the right format
- Save images at the right size
- Measure images in pixels

JPEG: Photos with many different colors
GIF or PNG: When saving images with few colors or large areas of the same color

<b>Chapter 11: “Color” (pp.246-263)</b><br />
RGB VALUES: Values for red, green and blue are expressed as numbers between 0 and 255.<br /> 
HEX CODES: Hex values represent values for red, green and blue in hexadecimal code. <br />
COLOR NAMES: Colors are represented by predefined names. However, they are very limited in number<br />
HUE: Near to the colloquial idea of color. A color can also have saturation and brightness as well as a hue.<br />
SATURATION: Refers to the amount of gray in a color. At max saturation, there would be no gray in the color. At minimum saturation, 
the color would be mostly gray. <br />
BRIGHTNESS: Or "value" refers to how much black is in a color. At maxiumum brightness, there would be no black in the color. 
At minimum brightness, the color would be very dark. <br />

- It's important to make sure that there is enough contract between any text and the background color. Otherwise, people will not be able to read your content.
- CSS3 introduced an extra value for RGB colors to indicate opacity. It's known as RGBA.
- CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It's known as HSLA. 


<b>Chapter 12: “Text” (pp.264-299)</b><br />
- When choosing a typeface, browsers will usually only display it if its installed on that users computer. 
- You can specify a list of fonts separated by commas so that if the user doesn't have your first choice of typeface installed, the browser can try to use
an alternative font from the list.

There are three units of type size:
1) Pixels (Best way to ensure you get the size you intended)
2) Percentages
3) Ems

text - transform: Property is used to change the case of text, giving it either values:
- uppercase
- lowercase
- capitalize

- If you want to use a wider range of typefaces, there are several options that require the right license to use.
- You can control the space between lines of text, individual letters and words. Text can also align to the left, right, center or justified. It can also be
indented.
- You can use pseudo classes to change the style of an element when a user hovers over or clicks on text, or when they have visited a link. 



