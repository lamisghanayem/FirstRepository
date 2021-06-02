# Debugging in JS

1. To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.
2. In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's v a ri ables object.
3. If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handl ing code. 
4. The JavaScript console is just one of several developer tools that are found in all modern browsers. 
5. The console will show you when there is an error in your JavaScript. It also displays the line where it became a problem for the interpreter.
6. JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error. 