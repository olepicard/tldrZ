# VIRHT51I linename CONNECTING termname TO ipaddr:port
Module
    VIRHTTP
Meaning
    An incoming or outgoing HTTP call is being processed. For an incoming HTTP call, linename is the external name of the HTTP line, termname is the name of the VIRTEL terminal allocated to process the call, and ipaddr:port is the IP address and port number of the client browser. For an outgoing HTTP call, linename is the external name of the HTTP outbound line, termname is the name of the VIRTEL terminal making the call, and ipaddr:port is the IP address and port number of the remote HTTP server. This message can be suppressed by the SILENCE parameter in the VIRTCT.
Action
    None.
