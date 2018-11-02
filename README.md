# notes_on_this_and_object_protoypes
Notes from reading Kyle Simpson's You Don't Know JS - this &amp; object prototypes

'this' = Javascript this keyword.

Chapter 1

You can somewhat avoid using 'this' by leveraging lexical scope and ES6 arrow functions. However, this often makes for inferior code and a good understanding of 'this' is important in beng a proficient JavaScript developer.

'this' is not a synonym for an object referencing itself. Neither is 'this' a reference to an object's lexical scope.

'this' is not an author time binding but a runtime binding. It is a contextual based on the condtions of the function's invocation/ 'this' binding has nothing todo with whether a function is declared, but everything to do with the manner in which the function is called.

When a function is invoked, an activation record, otherwise known as an execution context, is created. This record contians information about where the context is, created. This record contains information about where the function was called from the call stack, how the function was invoked, what parameters were passed etc. One of the properties of this record is the 'this' reference, which will be used for the dureation of that function's execution.

Chapter 2


