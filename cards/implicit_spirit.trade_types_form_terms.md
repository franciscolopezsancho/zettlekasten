2004. Implicit conversion
We can not extends after the fact two classes exists, so let's create an automatic wrapper.

implicit def c2t(x: C) = new T{...}

2006. Implicit parameters to create type classes in an OO programming language. Implicit parameter over an implicit parameter.


show[A](list: List[A])(implicit s: Show[A]): String

show(List(1,2,3))(intShow)

Links:

[Implicit Resolutions](implicit_resolutions.md)

[Type class](type_class.md)


Source: https://www.youtube.com/watch?v=uPd9kJq-Z8o

Author: [Martin Odersky](../authors/martin_odersky.md)