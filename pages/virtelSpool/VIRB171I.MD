# VIRB171I LINE linename (n-xxxxxx) IS WAITING FOR m-yyyyyy ACTIVATION

`Module`
- VIR0B17

`Meaning`
- Initialisation of the line with external name linename and internal name n-xxxxxx is waiting for line m-yyyyyy to start, because WAIT-LINE(m-yyyyyy) was specified in the “Startup prerequisite” field in the definition of line n-xxxxxx.

`Action`
- Activate line m-yyyyyy, or wait until VIRTEL activates it.
