A type class is polymorphic parametrization with overloading. It will allow you to enrich a class after the fact it exists and in scala is made with:
Trait with parametric polymorphism
A dictionary of implicit objects/vals that overload the trait
Optionally an implicit class that will use conversion to create an instance of the Dictionary that has the above referred overloaded method

Source: https://typelevel.org/cats/typeclasses.html

Author: https://typelevel.org/cats