# Acid Isolation (REVIEW)
Serializable, comes from serial, one after another. And avoids the write skew. No transaction is affected by any other in the sense the the reads that beging with have to stay the same until its writes and commit happens.

Repeatable read will block the rest of the DB while in its same level Snapshot Isolation or MVCC will be consistent in the reads of an specific version. These two avoid reads skews which could happend in iterleaved reads.

Read write committed will avoid a dirty reads these means uncommited reads. And dirty writes.

Read write uncommited avoids nothing.

[Source](https://www.youtube.com/watch?v=5ZjhNTM8XU8)

[Author]: authors/martin_kleppman.md

[link]: serializability_on_a_triangule.md