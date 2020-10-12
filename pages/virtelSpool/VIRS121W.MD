# VIRS121W termid ERROR LOADING SCENARIO modname IN TRANSACTION tranid

`Module`
- VIR0S12

`Meaning`
- Transaction tranid at terminal termid called for a presentation module modname which could not be loaded.

`Action`
- Check the log for a previous message VIR0031W. Check the module name specified in the “Initial Scenario”, “Final Scenario”, “Input Scenario” or “Output Scenario” field of transaction tranid. Ensure that this module exists in the VIRTEL load library and that it contains a valid scenario of the requested type. Recompile the module using the current version of the VIRTEL SCRNAPI macro library.
