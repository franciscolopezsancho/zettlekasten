Inlining and factoring out is referential transparency. This is the definition of a function. This is how you find there are no side effects. 

Categories as arrows, objects, identity, and associativity allow us to construct functional programs that we can prove correct on building and after changing.

But with these nice properties we lost the ability to express Exceptions, Partiallity, NonDeterminism, Dependency Injection, Logging, Mutable state, the simplicity of imperative programming.

Not how we do use functional constructs to those objects that give us back that expressiveness through: 
Option[B] as Partialilty
Either[B] as Exceptions 
List[B] (not as data structure but function with multiple answers? no surjective right?
Reader[Config, B] is Dependency injection
Writer[Info, B] is Logging
State[Info, B] as Mutable state

But wait, now we lost composition. Now is Monads come into play

Links:
[Category as four musketeers](categories_as_four_musketeers.md)
[Kleisi to link higer kinded functions](kleisi_to_link_higher_kinded_functions.md)


Author: [Rob Norris](authors/../../authors/rob_norris.md)

Source: https://www.youtube.com/watch?v=30q6BkBv5MY&t=1514s&ab_channel=ScalaDaysConferences