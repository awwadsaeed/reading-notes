# Debugging
## scope and order of execution
there are 2 scopes in js. one is Global scope and the other is function scope.  
variables created in global scope can be used any where even inside funcitins.  
however function sope variables can only be used inside the funciton and not outside.  
using them out side will give you an error of not difined, because they have not been declared and can only be seen indise the function.  
javascript interpeter executes the code line by line but when met with a fuction code it goes to that function scope and execute whatever code in it. and then go back to continue from before.  
if met with a funciton call inside a function that has been called this is the order of execution:  
- it goes normally until it meets the first function call.
- it goes into that function scope and executes it.
- it meets the second function call inside the first function execution.
- it goes to the second function scope and execute it.
- it goes back to first function scope and continue its execution.
- after finishing executing the first function scope it continues normally. 