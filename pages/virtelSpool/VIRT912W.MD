# VIRT912W linename SOCKET socknum STARTED FOR ipaddr:port
Module
    VIR0T09
Meaning
    VIRTEL has opened TCP/IP socket socknum on the line with external name linename. If socknum is 00000000 then this is a listening socket, port is the listening port number, and ipaddr is the IP address on which VIRTEL accepts incoming connections (000.000.000.000 means that VIRTEL accepts connections on any of the host’s home IP addresses). If socknum is non-zero and port is non-zero, then this is an incoming connection, and ipaddr:port is the client’s IP address and port number. If socknum is non-zero and port is 00000, then this is an outgoing connection, and ipaddr is VIRTEL’s  IP address (000.000.000.000 means that VIRTEL is using the host’s default home address).  For VIRTEL 4.33 onwards, this message is replaced by messages VIRT905I, VIRT906I and VIRT907I respectively. This message can be suppressed by the SILENCE parameter in the VIRTCT.
Action
    None.
