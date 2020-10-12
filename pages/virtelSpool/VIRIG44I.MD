# VIRIG44I termid luname CLEAR RECEIVED FROM LOCAL applname CAUSE=xx DIAG=yy

`Module`
- VIR00IG

`Meaning`
- VIRTEL received an X25 CLEAR command from the CTCP application applname. The command was received on the data session with CVC relay LU name luname associated with AntiGATE terminal termid. xx and yy are the X25 cause and diagnostic codes in hexadecimal. This message is suppressed if the cause and diagnostic codes are zero and the SILENCE parameter is specified in the VIRTCT.

`Action`
- If the cause and diagnostic codes are zero, this indicates a normal end of call. Otherwise, use the cause and diagnostic codes to determine why the CTCP application issued the CLEAR.
