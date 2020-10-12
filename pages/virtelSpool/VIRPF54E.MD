[VIRPF54E INVALID REQUEST ON linename ENTRY POINT 'epname' DIRECTORY 'dirname'](https://virtel.readthedocs.io/en/latest/manuals/virtel/Virtel459MG/messages.html?highlight=VIRPF54E#VIRPF54E)

`Module`
- VIR0PRF

`Meaning`
- VIRTEL received a request on the line whose external name is linename. The requested directory path dirname does not exist under the entry point epname.

`Action`
- Check the definition of the entry point epname. Ensure that there is a type 4 transaction with external name dirname.
