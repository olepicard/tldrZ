# VIRPS16I linename RECEIVED REJECT CONNECT REQUEST FOR 'termname' WITH DIAGNOSTIC :'hexcode' ('deccode')
`Module`
- VIRPESIT
`Meaning`
- A file transfer request via the VIRPESIT line whose external name is linename has been rejected by the partner file transfer application. termname is the terminal name, hexcode is the hexadecimal abort code and deccode is the decimal abort code.
`Action`
- Inspect the logs of the file transfer application to determine why the application terminated the transfer. Refer to the file transfer application’s protocol documentation to determine the meaning of the abort codes.
