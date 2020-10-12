[VIRI914E termid ERROR R15=xx R0=yy CONNECTING luname TO applid](https://virtel.readthedocs.io/en/latest/manuals/virtel/Virtel459MG/messages.html?highlight=VIRI914E#VIRI914E)

`Module`
- VIR0I09

`Meaning`
- VIRTEL could not establish a session between VIRTEL LU luname and the ACB applid of a partner application. xx et yy are the hexadecimal error codes from REQSESS.

`Action`
- If R15=00000020, activate the LU luname in VTAM, then enter a VIRTEL START command for the line. For any other value of R15, check that the application applid is active and ready to receive connections, and that the LU luname is in CONCT status.
