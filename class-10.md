From the Duckett JS book
JavaScript book, Ch. 10, “Error Handling & Debugging”

## Order of Execution
Finding the source of the issue can be easy when you understand the order of how task are completed or generated 
and when it can be used.
there are global contexts and function specific contexts. There are also function generated context

## Execution contexts

-Global context. This is a a script that does not live in a function. There can only be one global context in any page

-Function context This is code that is runned inside a function. Each function has it's own function context.


## Variable Scope

- Global scope. when a variable is placed outside of a function it can then be used anywhere. if you dont use the `var` keyword it is then place in a global scop.

- Function-level scope.  when a variavble is set inside a fucntion it is then set only in that function.

## Understanding the errors 

- When JavaScript generates an error the interpreter stops and looks for an exception-handling code
