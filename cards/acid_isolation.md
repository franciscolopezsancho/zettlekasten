# Acid Isolation

There are four levels of Isolation used to tackle different problems that when dealing with transactions. 
This problems are:
**Write Skew** that is like a read skew with a write inside the transaction. So when a premise used to choose a write can be altered before the write gets commited. 

**Read Skew** happens when a transaction interleaves reading a register that it's going to be changed inside another transaction that has already started but not yet commited.  

**Read (write) committed** will avoid that two transactions can alter the same register until one or the other has finished. Has commited. It avoids what it's called **Dirty Writes**.

**Read (write) uncommited** avoids nothing.

Links: 
[Serializable](serializable.md)
[Repeatable Read and Snapshot Isolation](repeatable-read_snapshot-isolation.md)


[Source](https://www.youtube.com/watch?v=5ZjhNTM8XU8)

[Author](../authors/martin_kleppman.md)
