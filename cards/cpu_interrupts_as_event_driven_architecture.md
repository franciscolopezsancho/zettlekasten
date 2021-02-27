An interrupt at CPU level is meant to avoid polling to peripherals that run at a speed orders of magniture slower. Asking the question to one of this externals pieces would take forever until the CPU gets an answer out of them. A solution to this problem, pervasive in the industry of software, is to react to events. The main program, under the exception that an interrupt is, saves its context generally in a stack and goes with the index of that interrupt to a table where lays the code that matches the type of that peripheral event, the Interrupt Service Handler or Routine, ISR. Once it finishes running that code recovers the context from the stack and continues processing. 
Not to forget that the ISR is a table with multiple event order by priority and that goes in its execution as a FSM, for instance inactive->pending->active->active&pending
Last but not least, there are not only interrupts for peripherals but for communication among processors called in ARM architecture Software Generated Interrupts SGI.  


Why a operating system doesn't stop under exceptions? is just a degraded system?
What's happening with Exceptions? how do they handle them, also a degraded system?

Link:
[Concurrent](concurrent.md)

Source:
[An introduction to interrupts](https://www.youtube.com/watch?v=jMnuQMYR3Ro&ab_channel=EliHughes)
[3.2. General Handling interrupts](file:///Users/francisco/Downloads/IHI0048B_b_gic_architecture_specification.pdf)

Author: N/A
