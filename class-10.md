From the Duckett JS bookJavaScript book, Ch. 10, “Error Handling & Debugging”


## Order of ExecutionFinding the source of the issue can be easy when you understand the order of how task are completed or generated and when it can be used. There are global contexts and function specific contexts. There are also function generated context

## Execution contexts

-Global context. This is a a script that does not live in a function. There can only be one global context in any page

-Function context This is code that is running inside a function. Each function has its own function context.

## Variable Scope

- Global scope. when a variable is placed outside of a function it can then be used anywhere. if you don't use the `var` keyword it is then place in a global scope.

- Function-level scope. when a variable is set inside a function it is then set only in that function.

## Understanding the errors

- When JavaScript generates an error the interpreter stops and looks for an exception

-handling code
