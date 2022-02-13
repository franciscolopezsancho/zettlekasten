- Behavior can change when conflict names of an implicit value with a normal param of a function in the same scope
- Nesting. If there's imp param in a def and also imp val with same type, ambiguity occurs
- It's used to create conversion methods but also to create conditional conversions (which is an impl def with an impl param). Two conversions.
- Implicit params are too close to normal params, such as calling a function that has an imp param that return a function. Passing a param is not clear if is the implicit or the param to the function it returns
- Importing with a wildcard `mylibrary._` is very powerful for writers but very obscure for end-users.

Source: https://www.youtube.com/watch?v=uPd9kJq-Z8o
[](goto_inconveniences.md)

Authors: [Maring Odersky](../authors/martin_odersky.md)