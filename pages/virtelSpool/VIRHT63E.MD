# VIRHT63E linename ERROR STARTING PSEUDO FOR PREFIX $LINE$ FOR TRANSACTION ttttttt (xxxxx)
Module
    VIRHTTP
Meaning
    The VTAM terminal (relay) to use for a request is already active for another session. The request was received on line linename for transaction ttttttt.
Action
    The request cannot be satisfied. The connection is closed. Run a /F stcname,snapmsg,all command at the console.
