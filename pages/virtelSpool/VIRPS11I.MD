# VIRPS11I linename PSEUDO termname RECEIVED ABORT REQUEST FROM emitter TO receiver WITH FIRST ABORT PID : pid

`Module`
- VIRPESIT

`Meaning`
- VIRTEL received an abort request of type pid via terminal termname associated with the VIRPESIT line whose external name is linename. Emitter is the name of the file transfer requester and receiver is the name of the destination partner.

`Action`
- The file transfer terminates. Inspect the emitter logs to determine why the partner application terminated the transfer.
