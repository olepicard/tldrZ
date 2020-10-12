[VIRIC54E linename IMS STATUS ERROR 'retcode' REASON 'reascode' text](https://virtel.readthedocs.io/en/latest/manuals/virtel/Virtel459MG/messages.html?highlight=VIRIC54E#VIRIC54E)

`Module`
- VIR0ICON

`Meaning`
- VIRTEL attempted to start the IMS Connect line whose external name is linename. The RESUME TPIPE request was rejected by IMS Connect with return code retcode and reason code reascode. A brief explanation of the code is displayed as text if the return code and reason code are known to VIRTEL.

`Action`
- Check the OTMAPRM parameter in the VIRTCT. Check the IMS Connect log for error messages. If the error is NACK_RSM_TPIPE_SEC_FAILED check for ICH408I and IRR012I messages in the system log.
