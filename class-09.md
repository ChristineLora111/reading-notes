## Read 09: Forms and JS Events:
[Go back to Reading Notes home](README.md)

<b><h3>HTML/Chapter 7: “Forms” (p.144-175)</h3></b>
What is a form? : "Printed document that contains spaces for you to fill in information"

There are different types of form controls that you can use to collect information from people visiting your site:
- Adding Text: text input (single line), password input, text area (multiple line)
- Making Choices: radio buttons(selecting one from a number of options), checkboxes, drop-down boxes
- Submitting Forms: submit buttons, image buttons, uploading files

< form >: this element always carries the action attribute, will normally have a method and id attribute.
- < form action=" example URL " method ="get" > < p > whatever text you want < /p > < /form >

action: 
- every form element requires an action attribute. The value is the URL for the page on the server that will receive the information
in the form once it's submitted.

method:
- forms are sent using either one of these methods: get or post

< input >: this element is used to create different form controls. The value of the type attribute determines what kind of input it will be creating.
- < input type =" the text " name =" username for example " size =" 15 " maxlength =" 30 " />
- this would be within the form element

type = an attribute that determines what type of form it will be. EX: password, checkbox, radio (user has to pick one from number of options)
text = single line input
name = the value of this attribute identifies the form control and is sent along with the information they enter to the server
maxlength = this attribute can be used to limit the number of characters a user can enter in the text field. 
value = this attribute indicates the value that will be sent to the server if the check box or answer is sent

HTML5 introduces new form elements which make it easier for visitors to fill in forms. 


<b><h3>HTML/Chapter 14: “Lists, Tables & Forms” (pp.330-357)</h3></b>

CSS properties that work with the contents of all elements are just one of several others that are specifically used to control and appearances of tables, forms and lists. 

List markers can be given different appearances.
This is done using the list-style-type and list-style image properties

Table cells can have different borders and spacing in different browsers. 
There are properties that can be used to control them and make it so they are more consistent. 

Forms are apparently more easier to use if the form controls are vertically aligned using CSS

Forms benefit from styles that make them feel more interactive. 

Bullet point style:
- list-style-type

Images for bullets:
- list-style-image

Properties of a table:
- width
- padding
- text-transform
- letter-spacing, font-size
- border-top, border-bottom
- text-align
- background-color
- :hover 



<b><h3>JS/Chapter 6: “Events” (pp.243-292)</h3></b>
- Events are the browsers way of indicating when something has happened.
EX: when a page has finished loading or a button has been clicked

Binding:
- This is the process of stating which event you are waiting to happen.
- You're also waiting on which element you are waiting for that event to happen on.

When an event happens on an element, it can trigger a JavaScript function.
Once the function runs and it changes the web page in some way, it feels interactive because it has responded to the user.

** My thoughts **
- It's very interesting to know this because this is what we are constantly doing mindlessly everyday on our computers and phones, not realizing this is the what's happening under the hood without giving it much thoughts. It's incredibly complex. It's very interesting. 

You can use event delegation to monitor for events that can happen on all of the children of an element.

The most commonly used events:
- W3C DOM events
- others in the HTML5 specification
- Browser specific events












