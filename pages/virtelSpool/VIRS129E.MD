# VIRS129E termid ERROR: SCENARIO scenname ABENDED AT OFFSET 'xxxxxxxx' ON INSTRUCTION STARTING WITH 'yyyyyyyy' [INPUT|OUTPUT|IDENTIFICATION SCENARIO IS DISCARDED]
Module
    VIR0S12
Meaning
    The scenario scenname invoked from terminal termid contains an instruction which is invalid, or which attempted to perform an invalid operation such as copying into a protected field on the 3270 screen, or a MAP$ ABEND instruction was executed. xxxxxxxx is the hexadecimal offset within the module of the instruction. yyyyyyyy represents the first four bytes (in hexadecimal) of the instruction. The scenario is abandoned (as if SCENARIO DISCARD had been coded).
Action
    Check the assembly listing to verify that the scenario has been correctly assembled. Check that the correct level macro library was used.
