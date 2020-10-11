# VIRXO05E linename UNDEFINED PARTNER n.n.n.n:p IS CALLING m.m.m.m:q
Module
    VIRXOT
Meaning
    VIRTEL has rejected an incoming call from an XOT line. n.n.n.n:p represents the IP address and port of the caller (usually an XOT router), m.m.m.m:q represents the called IP address and port in VIRTEL. VIRTEL rejected the call because none of the XOT lines listening on address/port m.m.m.m:q specifies address n.n.n.n as partner.
Action
    Define an XOT line specifying m.m.m.m:q in the “Local ident” field and n.n.n.n:1998 in the “Remote ident” field. If necessary, use the xot-source parameter of the x25 route instruction in the router to ensure that the router presents the expected address to VIRTEL in its incoming calls. For additional information, refer to the section “Defining an XOT line” in the VIRTEL Connectivity Reference manual.
