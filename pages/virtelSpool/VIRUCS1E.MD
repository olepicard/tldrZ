[VIRUCS1E termid COULD NOT FIND TRANSLATION TABLE tablename](https://virtel.readthedocs.io/en/latest/manuals/virtel/Virtel459MG/messages.html?highlight=VIRUCS1E#VIRUCS1E)

`Module`
- VIR0UCS

`Meaning`
- Translation table tablename requested by terminal termid was not found.

`Action`
- Check that the CODEPAGE parameter of the URL contains a valid translation table name, and that the table has been loaded by VIRTEL at startup, either as standard, or by the CHARSET parameter of the VIRTCT (see “Parameters of the VIRTCT” in the VIRTEL Installation Guide).
