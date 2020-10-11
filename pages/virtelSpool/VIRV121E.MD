# VIRV121E termid COULD NOT FIND TRANSLATION TABLE 'tablname' FOR PAGE 'pagename' DIRECTORY 'tranid' (dirname)
`Module`
- VIR0V12
`Meaning`
- The HTML page pagename in the directory referenced by the transaction with external name tranid and internal name dirname specifies an unknown translation table tablname.
`Action`
- Check that the table tablname specified in the SET-OUTPUT-ENCODING-UTF-8 instruction in the HTML page was loaded into VIRTEL at startup time, either as standard, or by being specified in the CHARSET parameter of the VIRTCT (see the VIRTEL Installation Guide manual).
