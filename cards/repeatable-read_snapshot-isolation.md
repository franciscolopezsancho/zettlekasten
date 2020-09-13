 This is tackled through **Repeatable Read** that blocks from read every register that is changed inside a transactions until it commits. Also more ofter is used 'MultiVersionConcurrencyControl' or **Snapshot Isolation** that versions everything that changes in a transaction and then allows another read transaction to verify that all it's read belong to the same version. If not it will get executed again. 


[Source](https://www.youtube.com/watch?v=5ZjhNTM8XU8)

[Author]: authors/martin_kleppman.md