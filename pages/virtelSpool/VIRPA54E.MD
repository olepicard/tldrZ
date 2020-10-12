[VIRPA54E termid INVALID REQUEST ON linename FROM CALLER ipaddr:port ENTRY POINT 'epname' TRANSACTION OR SERVER 'servid'](https://virtel.readthedocs.io/en/latest/manuals/virtel/Virtel459MG/messages.html?highlight=VIRPA54E#VIRPA54E)

`Module`
- VIR0PASS

`Meaning`
- VIRTEL received an incoming call on terminal termid associated with the VIRPASS line whose external name is linename. The call originated from IP address ipaddr port port. The service requested was servid. But the chosen entry point epname contains no transaction whose external name is servid, nor does it contain a default transaction capable of invoking the external server named servid.

`Action`
- Check that entry point epname has been defined in accordance with the documentation for setting up the VIRTEL Videotex Plugin.
