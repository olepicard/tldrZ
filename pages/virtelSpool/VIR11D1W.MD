# VIR11D1W termid ERROR LOADING SCRIPT scriptnam IN TRANSACTION tranid
`Module`
- VIR0011D
`Meaning`
- Transaction tranid at terminal termid called for a scenario module which could not be loaded.
`Action`
- Check the log for a previous message VIR0031W. Check the module name specified in the “Input Message Exit” or “Output Message Exit” field of transaction tranid. Ensure that this module exists in the VIRTEL load library and is a valid scenario module. Recompile the scenario using the current version of the VIRTEL SCRNAPI macro library.
