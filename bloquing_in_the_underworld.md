What is blocking in an upper level (t1 waiting for t2) is a sequential not consecutive call in  layer  below. 
To coordinate these waits you need scheduling that can be preemptive (external suspension) or cooperative (autosuspension). Fibers have the latter.

[Source](https://youtu.be/x5_MmZVLiSM?list=LL30eQanWW-SQt5XeLKb596Q&t=1062)

Author: [Fabio Labella](authors/fabio_labella.md)