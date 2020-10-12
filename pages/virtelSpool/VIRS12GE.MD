[VIRS12GE CANNOT RESOLVE PASSTICKET OF TYPE 'applname' ABORTING SCENARIO](https://virtel.readthedocs.io/en/latest/manuals/virtel/Virtel459MG/messages.html?highlight=VIRS12GE#VIRS12GE)

`Module`
- VIR0S12

`Meaning`
- VIRTEL was unable to process an instruction of type PASSTICKET-FOR-TRANSACTION contained in a scenario.

`Action`
- Possible causes are: (1) Not signed on (2) Transaction not found (3) No application name in transaction (4) PASSTCK not specified in VIRTCT (5) Application name not found in PASSTCK table (6) Request is neither GENERATE nor EVALUATE (7) Request specifies GENERATE or EVALUATE but does not match corresponding entry in the PASSTCK table (8) Insufficient storage for workarea (9) Error linking to module IRRSPK00
