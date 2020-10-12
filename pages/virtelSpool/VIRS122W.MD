[VIRS122W termid INVALID FA39 SCENARIO RECEIVED](https://virtel.readthedocs.io/en/latest/manuals/virtel/Virtel459MG/messages.html?highlight=VIRS122W#VIRS122W)

`Module`
- VIR0S12

`Meaning`
- The transaction at terminal termid called for a presentation module which was not valid.

`Action`
- Check the module name specified in the “Initial Scenario”, “Final Scenario”, “Input Scenario” or “Output Scenario” field of the transaction. Ensure that this module contains a valid scenario of the requested type. Recompile the module using the current version of the VIRTEL SCRNAPI macro library.
