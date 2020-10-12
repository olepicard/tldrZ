[VIRPS12I linename RECEIVED ABORT REQUEST FOR termname (partnerid)](https://virtel.readthedocs.io/en/latest/manuals/virtel/Virtel459MG/messages.html?highlight=VIRPS12I#VIRPS12I)

`Module`
- VIRPESIT

`Meaning`
- VIRTEL received an abort request via the VIRPESIT line whose external name is linename. termname is the terminal name and partnerid is the name of the destination partner.

`Action`
- The file transfer terminates. Inspect the logs of the file transfer application to determine why the application terminated the transfer.
