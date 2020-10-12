# VIRI907I luname(termid) REJECTED BIND FROM applname

`Module`
- VIR0I09

`Meaning`
- The relay LU luname associated with VIRTEL terminal termid received an unsolicited SNA BIND command from application applname. VIRTEL rejected the BIND because the LU was not expecting to receive a session request from applname. This can occur if a PCNE application is attempting to place an outgoing call to an LU reserved for incoming calls.

`Action`
- Check that the application has specified the correct LU name. Check that “possible calls” is not set to “2” in the VIRTEL terminal definition.
