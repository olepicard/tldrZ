# VIRS125E termid VIRSV REQUEST ERROR – R15 : xxxxxxxx (dddddddd)
`Module`
- VIR0S12
`Meaning`
- A scenario invoked from terminal termid was unable to call a service program using the VIRSV$ macro instruction. xxxxxxxx is the hexadecimal return code from program VSVPREQS, and dddddddd is the decimal equivalent of the low-order byte of the return code.
`Action`
- Refer to the VIRSV User’s Guide manual to determine the meaning of the VSVPREQS return code. Check the VIRTEL log and the VSVTRACE file for additional messages. Check that the requested service program exists in a load library in the SERVLIB concatenation of the VIRTEL started task JCL. If VIRTEL runs as an APF-authorized task, check that the load library containing the service program is APF-authorized.
