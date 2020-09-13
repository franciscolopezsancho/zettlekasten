trait Functor[F[_]] = {
     def map[A,B](value: F[A])(f: A => B): F[B]
}

trait Monad[F[_]] = {
def pure[A](value: A): F[A])
def flatMap[A,B](value: F[A](f: A => F[B]): F[B] // implies order
 }

trait Applicative[F[_]] = {
def pure[A](value: A): F[A]
def ap[A,b](value: F[A])(f: F[A] => F[B]): F[B] // does not imply order
}

trait Monoid[A] = {
      def identity(a: A): A
      def compose(a: A, b: A): A
}// Is just one “object” in category theory, were there’s only arrows and objects. Looking from set theory to category theory, tough, that “single” objects is a set.

(No refs.)

Links:

[Kliesi to link higher kinded functions](kleisi_to_link_higher_kinded_functions.md)