Goto are like functions with no input and the incapability of returning to the same point where the GOTO call was made. These two combined, difficult reading the code. 
First, because after jumping to a new point with no input you need to retrace the variables in scope used in this new code you're just WENTTO. 
Second, because once there you lost trace from where you came from, is just more difficult to retrace it in space. To find how did you get there. As Djistra[^1] rightly pointed out, it's somehow easy for humans to trace a program in space while not in time. GOTOs diminishes our spacial performace, the only of the two we are good at.

[](implicit_resolutions.md)

[^1]Go to statement considered harmful(https://homepages.cwi.nl/~storm/teaching/reader/Dijkstra68.pdf)