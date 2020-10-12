# VIRHT53E linename NO MORE PSEUDO FOUND WITH PREFIX xxxx FOR TRANSACTION tranname(tranid)

`Module`
- VIRHTTP

`Meaning`
- VIRTEL tried to open a terminal whose name matches the prefix xxxx specified in the VIRTEL transaction with external name tranname and internal name tranid, but this prefix conflicts with the prefix specified on the definition of the HTTP line whose external name is linename.

`Action`
- Check the “Prefix” field of the HTTP line and the “Pseudo-terminals” field of the transaction.
