Serializability on a triangle

Let's put out there three different serializability solutions. 

    Lock all the things
    Make sequential each transaction one after the other, a bit pessimistic, 
    Keep log of every transaction and before commit check it has not conflicts, if it has replay it. Kind of optimistic but if there's many conflicts will produce contention.  

[Source](https://www.youtube.com/watch?v=5ZjhNTM8XU8)

[Author]: martin_kleppman.md