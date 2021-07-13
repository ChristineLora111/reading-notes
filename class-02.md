## Reading notes from the Duckett HTML book:
[Go back to Reading Notes home](README.md)

<b>Chapter 2: “Text” (pp.40-61) Summary:</b>
- HTML elements are used to describe the structure of the pages such as headings, subheadings, paragraphs, etc.
- Structural markups: include elements such as h1, h2 and p They are elements that you can use to describe both headings and paragraphs.
- Semantic markups: Provide extra information such as where emphasis is placed in a sentence, that something you have written is a quotation and who said it,
the meaning of acronyms, etc.

<b>Chapter 10: Ch.10 “Introducing CSS” Summary + Notes:</b>
- To understand how CSS works, you have to imagine there's an invisible box around every HTML element. 
  Difference between block level elements and inline elements:
  - Block Level Element: Look like they start on a new line (EX: h1-h6, p and div elements.
  - Inline Elements: Flow within the text and do not start on a new line (EX: b, i, img, em and span.
- CSS allows you to create rules that control the way that each individual "box" and the content of it, is presented.
- CSS rules contain 2 parts: A selector and declaration
  
  "SELECTOR --> p {
                 font family: Arial;} <--- DECLARATION"
                                           
 This rule indicates that all p elements should be shown in the Arial type face.
 SELECTORS: Indicate which element the rule applies to. The same rule can apply to more than one element if you separate the element names with commas
 DECLARATIONS: Indiciate how the elements reffered to in the selector should be styled. Declarations are split into two parts (a property and a value) 
 and are separated by a colon. 
  
  Declarations sit inside curly brackets and each are made up of 2 parts: a PROPERTY and a VALUE, separated by a colon. 
  You can specify several properties in one declaration.
  
  h1, h2, h3 {
             font-family: Arial:
             colors:     yellow;}
             ^^PROPERTY   ^^VALUE
  
  This rule indicates that all h1, h2 and h3 elements should be in the Arial font, in yellow.
  
  PROPERTIES: indicate the aspects of the element you want to change like color, font, width, height and border.
  VALUES: Settings for the chosen properties, ex: color properties value would be yellow.
  
  <b>ADDITIONAL RESOURCES: Creating a Great Git Commit Message Notes. How to write the best ones! (According to Chris Beams, author of: https://chris.beams.io/posts/git-commit/)</b> 
  1) Separate subject from body with a blank line
  2) Limit the subject line to 50 characters
  3) Capitalize the subject line
  4) Do not end the subject line with a period
  5) Use the imperative mood in the subject line
  6) Wrap the body at 72 characters
  7) Use the body to explain what and why vs. how
  
  
  
  
