# VIRP121E PAGE NOT FOUND FOR termid ENTRY POINT 'epname' SCENARIO 'scenname' DIRECTORY 'tranid'(dirname) NAME 'filename' URL'url'
`Module`
- VIR0P12
`Meaning`
- The scenario scenname invoked from terminal termid requested a file named filename which does not exist. dirname is the name of the current VIRTEL directory and tranid is the external name of the corresponding transaction which belongs to entry point epname. VIRTEL sent a 404 NOT FOUND reply to the terminal with the text “Failed on missing page:filename”.
`Action`
- Change the scenario to specify the correct file name.
