[VIRPS56E linename IN ENTRY POINT 'epname', THE TRANSACTION 'partnerid' WAS NOT FOUND, AND THERE IS NO DEFAULT TRANSACTION](https://virtel.readthedocs.io/en/latest/manuals/virtel/Virtel459MG/messages.html?highlight=VIRPS56E#VIRPS56E)

`Module`
- VIRPESIT

`Meaning`
- An inbound file transfer session request was received on the VIRPESIT line whose external name is linename. The request was assigned to entry point epname, but the entry point has no transaction corresponding to the destination partner partnerid.

`Action`
- Correct the definition of the entry point, either by adding a transaction whose external name is partnerid, or by adding a default transaction whose external name is the same as the entry point name epname.
