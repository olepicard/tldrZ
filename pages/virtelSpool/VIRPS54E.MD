# VIRPS54E linename IN ENTRY POINT 'epname', TRANSACTION 'tranid', THE SERVER 'servname' WAS NOT FOUND

`Module`
- VIRPESIT

`Meaning`
- An inbound file transfer session request was received on the VIRPESIT line whose external name is linename.       The request was assigned to entry point epname and transaction tranid. The transaction calls for a server named servname (either explicitly, or by reference to the destination partner name specified by the file transfer application), but there is no external server definition of that name.

`Action`
- Add an external server definition for servname.
