RPC is about functions. It has lower latency as it works over TCP as but needs external documentation 
REST is all about resources -> Is a state machine over HTTP. It allows creation of imaginative clients to compose the access to these resources, but a bit chatty in this case. With http/2 seems this can be improve. Schema is on the call itself, autodocumented.
GRAPHQL is about queries -> where I can ask exactly what I want and bring back just those fields. Is autodocumented through an 'introspection' call to the __schema. 

Links:
[TCP basica](tcp_basics.md)

Sources:
https://www.youtube.com/watch?v=IvsANO0qZEg&ab_channel=OktaDev