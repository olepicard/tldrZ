# VIRCA17E termid CRYn **Error** servname retc=xxxx reas=yyyy
`Module`
- 	VIR0CA1
`Meaning`
- A call to an ICSF cryptographic service servname failed with return code xxxx and reason code yyyy. The return code and reason code are shown in hexadecimal.
`Action`
- Refer to SA22-7522 z/OS Cryptographic Services ICSF Application Programmer's Guide Appendix A for the meaning of ICSF return codes and reason codes. Return code 0000000C means that ICSF services are not available, usually because the CSF started task is not correctly initialized.
