[VIRB923E termid REQ|PARAM xxxx COMPLETION CODE code REASON CODE xxxxxxxx (dddddddd) LINE linename](https://virtel.readthedocs.io/en/latest/manuals/virtel/Virtel459MG/messages.html?highlight=VIRB923E#VIRB923E)

`Module`
- VIR0B09

`Meaning`
- A batch request has terminated abnormally. linename is the external name of the batch line, termid is the associated terminal name, type is the type of request, code is the abend code, xxxxxxxx is the reason code in hexadecimal and dddddddd is the decimal equivalent.

`Action`
- Inspect the console log for other error messages which may explain the cause. Contact technical support.
