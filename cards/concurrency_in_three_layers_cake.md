Three levels: 
1. os processes - M:N processors:processes,  have their own memory and execution state
2. jvm/os threads - M:N processes:threads, shared memory and own execution state
3.  fibers - M:N threads:fibers, share all

When change from one thread to another you have to store what you had and load what you’ll get. Their state. This is an expensive operation.
Fibers have nothing to store or keep so there’s no price to pay in switching.

Links:

[Blocking in the underworld](bloquing_in_the_underworld.md)

[Source](https://youtu.be/x5_MmZVLiSM?list=LL30eQanWW-SQt5XeLKb596Q&t=1062)

Author: [Fabio Labella](../authors/fabio_labella.md)