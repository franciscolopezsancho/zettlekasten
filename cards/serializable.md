**Serializable**, comes from serial, one after another is achieved by three diferent strategies. Literally avoiding concurrency running everything in order is a solution but you better be fast. **Two Phase Locking**, that will lock any read that happens inside the transaction. Finally **Serializable Snapshot Isolation** that is like 2pl but with versioning. 

Links:
[Serializable](serializability_linearizability.md)

[Source](https://www.youtube.com/watch?v=5ZjhNTM8XU8)

[Author](../authors/martin_kleppman.md)
