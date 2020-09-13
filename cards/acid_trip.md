# Acid Trip

This is all about transactions and their properties in a DB.

Atomicity has to do with abortabilty. All or nothing is achieve in presence of constraint violations, deadlocks, crashes or network failures.

Durability means it will persist after application shutsdown.

Isolation has four levels with five implementations. Serializable, snapshot isolation or repeatable read, read write committed and read write uncommited

Consistency, not the same from CAP. Is a property of the application that uses the DB. As keeping invariant a the output of a function. As the total balance to zero in an account.  

[Source](https://www.youtube.com/watch?v=5ZjhNTM8XU8)

[Author]: martin_kleppman.md

[link]: acid_isolation.md
