# VIRB177I LINE linename (n-xxxxxx) IS WAITING FOR m-yyyyyy ACTIVATION
Module
    VIR0B17
Meaning
    Initialisation of the line whose external name is linename and whose internal name is n-xxxxxx is waiting for line m- yyyyyy to start, because MIMIC-LINE(m-yyyyyy) is specified in the “Startup prerequisite” field in the definition of line n-xxxxxx.
Action
    Activate line m-yyyyyy, or wait until VIRTEL activates it.
