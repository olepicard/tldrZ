# VIRIC58E linename IN ENTRY POINT 'epname', THE TRANSACTION 'tranname' WAS NOT FOUND, AND THERE IS NO DEFAULT TRANSACTION
Module
    VIR0ICON
Meaning
    VIRTEL received a request on the IMS Connect line whose external name is linename. The request header specified transaction name tranname. The request could not be processed because the entry point epname does not contain a transaction whose external name is tranname, nor does it contain a default transaction whose external name is the same as the entry point name.
Action
    Correct the transaction name specified by the calling IMS program. Alternatively, in entry point epname add a transaction named either tranname or epname.
