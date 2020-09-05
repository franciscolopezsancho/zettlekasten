Function x -> c where c type is constant. Examples of this is a Predicate a -> boolean. Or Ordering.

A contravariant Functor would have:
famp :: (b -> a) -> Function a -> Function b

That should be read  as:
    if you have function from b to a and a Functor from a to const. I can build a Functor from b to const. Proceeding such as, you give me the b I'll transform to const through mapping b to a and a to const. 

[Source](https://youtu.be/JZPXzJ5tp9w?t=618)

Author: [George Wilson](authors/george_wilson.md)