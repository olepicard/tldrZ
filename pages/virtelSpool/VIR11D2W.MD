[VIR11D2W termid INVALID FA39 SCRIPT RECEIVED](https://virtel.readthedocs.io/en/latest/manuals/virtel/Virtel459MG/messages.html?highlight=VIR11D2W#VIR11D2W)

`Module`
- VIR0011D

`Meaning`
- The transaction at terminal termid called for a scenario module which was not valid.

`Action`
- Check the module name specified in the “Input Message Exit” or “Output Message Exit” field of the transaction. Ensure that this module contains a valid scenario of the requested type. Recompile the scenario using the current version of the VIRTEL SCRNAPI macro library.
