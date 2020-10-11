# VIRB924E termid OBJECT|PARAM nnnnnnnn REQ type COMPLETION CODE code REASON CODE xxxxxxxx (dddddddd) LINE linename
Module
    VIR0B09
Meaning
    An error or unexpected end of file was detected while reading the input file for a batch line. linename is the external name of the batch line, termid is the associated terminal name, type is the type of request, code is the abend code, xxxxxxxx is the reason code in hexadecimal and dddddddd is the decimal equivalent.
Action
    Check that the input file is correct.
