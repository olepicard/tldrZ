# VIRNA05E linename UNDEFINED PARTNER n.n.n.n:p IS CALLING m.m.m.m:q

`Module`
- VIRNATV

`Meaning`
- VIRTEL has rejected an incoming call to a native IP line. n.n.n.n:p represents the IP address and port of the caller, m.m.m.m:q represents the called IP address and port in VIRTEL. VIRTEL rejected the call because none of the TCP/IP lines listening on address/port m.m.m.m:q specifies address n.n.n.n as partner.

`Action`
- Define an XOT line specifying m.m.m.m:q in the “Local ident” field and n.n.n.n:p in the “Remote ident” field
