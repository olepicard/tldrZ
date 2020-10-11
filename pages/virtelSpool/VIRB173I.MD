# VIRB173I LINE linename (n-xxxxxx) STARTUP IS NOT AUTOMATIC
`Module`
- VIR0B17
`Meaning`
- Initialisation of the line whose external name is linename and whose internal name is n-xxxxxx is waiting for a START command, because WAIT-COMMAND is specified in the “Startup prerequisite” field in the definition of the line.
`Action`
- To activate the line, enter the VIRTEL command LINE=n-xxxxxx,START at the system console.
