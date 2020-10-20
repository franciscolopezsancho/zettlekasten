A Kleisli[F[_],A,B] is just a pattern created to wrap over A => F[B] to allow you to link it with another function of the same form. Let’s say Z => F[A]
So another Kleisli[F[_],Z,B] will allow you to be able to run a function such as Z => F[B] composing both Kleislies. 
This is composition with functions of the type Type => HigherKindedType. And depending of the higherKindedType, Monad, Functor, Applicative one can compose|flatMap, map or traverse, respectively. 

[Fp losing composition](fp_losing_composition.md)

[Source](https://typelevel.org/cats/datatypes/kleisli.html)

Author: [Cats: Kleisi](https://typelevel.org/cats/datatypes/kleisli.html)