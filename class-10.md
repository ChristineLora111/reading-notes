## Read 10: Forms and JS Events:
[Go back to Reading Notes home](README.md)

<b><h3>JavaScript book, Ch. 10, “Error Handling & Debugging”</h3></b>

Executation Context:
- global context
- function context
- eval context 

Variable Scope:
- global scope
- function level scope

Execution Context & Hoisting:
--- Each time a script enters a new execution context, there are two phases of activity ---
1) Prepare
2) Execute

Errors:
- If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code.

How to Deal with Errors? 
There are two things you can do with errors:
1) Debug the script to fix errors
- When you come across an error, this is where you will need to debug the code. Track down the source of the error and fix it. 
2) Handle errors gracefully
- Handle them using <i>try, catch, throw, and finally</i> statements

Content panels:
- They provide ways to show more content that is within a limited amount of area
Popular types of content panels:
- accordions
- tabs
- photo viewers
- modal windows
- sliders

What is advisable with website code?
- They recommend and advise you to separate you content, which is the HTML, the presentation, which is the CSS and behavior, which is the JavaScript into different files.

You can make objects to represent the functionality that you want.

You can turn functions in jQuery plugins that allow you to re-use code and share it with others.

Immediately invoked function expressions are used to contain scope and prevent naming collisions.

Debugging Tips:
1) Use a different browser
- Some errors are browser specific. Try the code in another browser to see which ones are causing a problem.

2) Add Numbers:
- Write numbers on the console so you can see which of the items get logged in. It'll show how far your code runs before you come across the error.

3) Strip it Back:
- Remove parts of the code and strip it down to the minimum you need. You can either remove the code all together or just comment it out using multi-line comments.

4) Explaining the Code:
- You usually find out the error when you're explaining the code to someone else.

5) Search:
- Stack Overslow is a great web resource for programmers or use a traditional search engine like Google.

6) Code Playgrounds:
- These help you try out code that you are suggested on forums.

7) Validation Tools for JavaScript:
- www.jslint.com
- www.jshint.com
