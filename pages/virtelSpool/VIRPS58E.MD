[VIRPS58E linename IN ENTRY POINT 'epname', THE EMULATION 'emtype' IS NOT SUPPORTED, SHOULD BE '$NONE$'](https://virtel.readthedocs.io/en/latest/manuals/virtel/Virtel459MG/messages.html?highlight=VIRPS58E#VIRPS58E)

`Module`
- VIRPESIT

`Meaning`
- An inbound file transfer session request was received on the VIRPESIT line whose external name is linename. The request was assigned to entry point epname, but the entry point specifies emulation type emtype which is not compatible with the VIRPESIT protocol.

`Action`
- Ensure that only entry points with emulation type $NONE$ are specified in the rules and in the line definition for a VIRPESIT line.
