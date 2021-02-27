Consensus over value v.
## Events:
- Request(v)
- Decide(v)
  
## Properties:
- Termination: every process eventually decides over value v
- validity: if decide(v) then request(v) must have happened
- integrity: no process decides(v) twice. {can't same value come back in the future?}
- agreement: no two correct process decide differently

Links:


Source:
https://youtu.be/2wSYcyWCtx4?list=WL&t=1898

Author:
[Jonas Boner](../authors/jonas_boner.md)