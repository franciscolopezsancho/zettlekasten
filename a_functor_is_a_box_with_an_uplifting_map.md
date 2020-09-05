A functor is a box. Is a lifter as it lifts f: a -> b, with Box(a) -> fmap(f) -> Box(b) 

It implies parametric polymorphism on  Box[_]. As there are many morphisms of that Box. Option[], List[], etc. On top of this is also ad-hoc polymorphism or overloading. Such as fmap implementation depends on its type, Int, String depending if is a Box[Int], or Box[String]

[Source](https://youtu.be/EO86S2EZssc?t=1392)

Author: [Bartosz Milesski](authors/bartosz_milewski.md)

Links:

[Monads add state and stop computations](monads_add_state_and_stop_computations.md)


[Contravariant Functor Prepends](contravariant_functor_prepends.md)