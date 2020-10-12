# VIRS124E termid VIRSV CREATE ERROR – R15 : xxxxxxxx (dddddddd)

`Module`
- VIR0S12

`Meaning`
- A scenario invoked from terminal termid was unable to call a service program using the VIRSV$ macro instruction. xxxxxxxx is the hexadecimal return code from program VSVPCREA, and dddddddd is the decimal equivalent of the low-order byte of the return code.

`Action`
- Refer to the VIRSV User’s Guide manual to determine the meaning of the VSVPCREA return code. Check the VIRTEL log and the VSVTRACE file for additional messages. Check the VIRTEL started task JCL to ensure that the VIRSV load library is referenced in both the STEPLIB and the SERVLIB concatenations. If VIRTEL runs as an APF-authorized task, check that the VIRSV load library is APF-authorized.
