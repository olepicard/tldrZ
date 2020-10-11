# VIRXO11I termid CLEAR RECEIVED FROM REMOTE linename CAUSE=xx DIAG=yy
`Module`
- VIRXOT
`Meaning`
- VIRTEL received an X25 CLEAR command from the router attached to the XOT line with external name linename. VIRTEL determined that the command was associated with CVC terminal termid. xx and yy are the X25 cause and diagnostic codes in hexadecimal. This message is suppressed if the cause and diagnostic codes are zero and the SILENCE parameter is specified in the VIRTCT.
`Action`
- If the cause and diagnostic codes are zero, this indicates a normal end of call from the remote partner. Otherwise, use the cause and diagnostic codes to determine why the router or the remote partner application issued the CLEAR.
