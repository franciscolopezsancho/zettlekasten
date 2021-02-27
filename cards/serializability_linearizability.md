Serializability is the possibility to express a transaction as a set of a set of operations over a set of objects as a sequence of operations, one after the other with an arbitrary total order. Therefore a program can run that arbitraly sequence.
Linearizability is the possibility of a set of operations over an object to be delineate like having order respect a common time, so any read will always give you the write before.  

Source:
[Pat helland]https://www.youtube.com/watch?v=V8TcEWdx2Q8&ab_channel=FunctionalTV
[Linearizability: A Correctness Condition for
Concurrent Objects ](http://cs.brown.edu/~mph/HerlihyW90/p463-herlihy.pdf)
[Linearizability vs Serializability](http://www.bailis.org/blog/linearizability-versus-serializability/#:~:text=Serializability%20is%20a%20guarantee%20about,over%20one%20or%20more%20objects.&text=Unlike%20linearizability%2C%20serializability%20does%20not,Serializability%20is%20also%20not%20composable.)

Links:
[Serializable](serializable.md)

Authors:
[Pat Helland](../authors/pat_helland.md)
[Maurice Herlihy](../authors/maurice_herlihy.md)


