[VIRPS15I linename RECEIVED REJECT CONNECT REQUEST FROM 'serverid' TO 'requesterid' WITH DIAGNOSTIC :'hexcode' ('deccode')](https://virtel.readthedocs.io/en/latest/manuals/virtel/Virtel459MG/messages.html?highlight=VIRPS15I#VIRPS15I)

`Module`
- VIRPESIT

`Meaning`
- A file transfer request via the VIRPESIT line whose external name is linename has been rejected by the partner file transfer application. serverid is the name of the destination partner, and requesterid is the name of the requesting partner. hexcode is the hexadecimal abort code and deccode is the decimal abort code.

`Action`
- Inspect the logs of the file transfer application to determine why the application terminated the transfer. Refer to the file transfer application’s protocol documentation to determine the meaning of the abort codes.
