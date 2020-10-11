# VIRS12FE termid ERROR: SCENARIO 'scenname' CALLS UNDEFINED TRANSACTION 'tranname' AT OFFSET 'xxxxxxxx'
Module
    VIR0S12
Meaning
    The scenario scenname invoked from terminal termid issued a SEND$ TO or SEND$ VARIABLE-TO instruction specifying an invalid transaction name tranname. xxxxxxxx is the hexadecimal offset of the SEND$ instruction within the module.
Action
    Verify that the entry point contains a type 5 transaction whose external name is tranname, or correct the transaction name in the scenario.
