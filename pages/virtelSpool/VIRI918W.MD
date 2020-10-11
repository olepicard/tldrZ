# VIRI918W RELAY luname(termid) INACTIVATED
Module
    VIR0I09
Meaning
    VIRTEL closed the relay luname for terminal termid following inactivation of the LU by VTAM.
Action
    Further connections using this relay will only be possible after the LU has been reactivated under VTAM, and a VIRTEL START command has been issued for the associated line, either from the “Status of lines” screen (F9 from the configuration menu, or F10 from the sub-applications system services menu), or by the console command LINE=linename,START.
