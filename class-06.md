## Read 06: Duckett JS book - Objects 
[Go back to Reading Notes home](README.md)

<b>Chapter 3: “Object Literals” (pp.100-105)</b><br />
Objects group together a set of variables and functions.

In an object, variables become PROPERTIES.
If VARIABLE --> Part of an OBJECT = PROPERTY
- Properties tell you about the object 
- (EX: name of a hotel or the number of rooms it has. Every hotel has a different name and number of rooms)

In an object, functions become METHODS.
If FUNCTION --> Part of an object = METHOD
- Methods represent the functionality and tasks that are associated with the object.
- (EX: You can check how many rooms are available by subtracting the number of booked rooms from the total number of rooms)

Both properties and methods have a name and value. 
- In an object, that name is called a KEY.
- An object cannot have two KEYS with the same name. 
- Keys are used to access their corresponding values.

Value of a property can be:
- String, number, Boolean, array or another object. 
- The VALUE of a METHOD is always a FUNCTION

PROPERTIES EX (Also the KEY): var hotel { <br />
      name: 'Motif', <br />
      rooms: 40, <br />
      booked: 25, <br />
      gym: true, <br />
      roomTypes: [ twin, double, suite ] <br />
      
METHOD EX: checkAvailability: function() { <br />
            return this.rooms - this.booked; }<br />
            
Member Operator:
- The property or method on its right is a member of the object on it's left. 
EX: var hoteName = hotel.name;
- OR - 
EX 2: var hotelName = hotel['name']
EX 2 ^^ is mainly used when a property/method has special characters like a dash
- OR - 
The name of a property is a number


<b>Chapter 5: “Document Object Model” (pp.183-242)</b><br />
DOM - Document Object Model
- Specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of the web page
while its in the browser window. 
- It is not part of HTML or JavaScript. 
- It has its on seperate set of rules

DOM Tree's:
- Has 4 types of nodes:
1) Document nodes
2) Element nodes
3) Attribute nodes
4) Text nodes

Element node:
- Can be selected by their ID or CLASS attributes by tag name or using CSS selector syntax
- You can access and update its content by using properties like textContent and innerHTML or using DOM manipulation techniques
- Can contain multiple text nodes and child elements that are siblings of each other.

DOM Query's
- Can return more than one node
- It's always NodeList

DOM can be inconsistent if using an older browser. This is why its populat to use jQuery. This can be usually seen in the browser, since 
most browser tools offer you to be able to view a DOM tree.

Elements that are found by methods in the DOM tree are called DOM QUERIES.
- This usually happens when you need to work with an element more than once. If this is the case, you will then need to use a variable to
store the result of the query.

getElementID() and querySelector()
- both search an entire document and return individual elements. They're both similar in syntax

There are only two ways to select an element from a NodeList:
1) item()
2) array syntax
They both require the index number of the element that is wanted.

