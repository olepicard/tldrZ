[VIRC122E ERROR termid IS SENDING A SCENARIO PF KEY BUT SCENARIO IS MISSING IN TRANSACTION 'tranid' ENTRY POINT 'epname'](https://virtel.readthedocs.io/en/latest/manuals/virtel/Virtel459MG/messages.html?highlight=VIRC122E#VIRC122E)

`Module`
- VIR0C12

`Meaning`
- Terminal termid sent an HTTP request containing a PF=SCENARIO parameter (see “Function key management” in  the VIRTEL Web Access Guide) but the transaction whose external name is tranid does not have an input scenario specified.

`Action`
- Add the name of an input scenario to the transaction tranid defined under entry point epname.
