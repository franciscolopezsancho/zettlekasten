Is a protocol, connection-oriented, end-to-end Works inter-process among diferent computers in diferent but inter-connected networks. 
Data is transfered as a continuous streams of octets, multiplexing, allowing creation multiple sockets ("tcp"/ip/port) to be used simultaneously in the same host. Provides reliability under data lost, duplicated, damaged or out of order, with sequences numbers (offset) and checksums, and flow control with a window (size of octets) under every ack. Conection is the combination of information of the  two sockets in play (unique id), size of windows, and sequence numbers involved.

Links:

[Classless is more, CIDR](classless_is_more.CIDR.md)
[Observationality equivalence to Session Types](observationaly_equivalence_to_sessions_types.md)


Source: https://tools.ietf.org/html/rfc793#section-1.5

Author: https://tools.ietf.org/html/