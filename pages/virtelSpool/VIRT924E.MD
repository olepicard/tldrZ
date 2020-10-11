# VIRT924E ERROR ON: linename SOCKET: socknum REQ: reqtype - RETCODE: FFFFFFFF ERRNO: xx (ddd)
Module
    VIR0T09
Meaning
    Socket socknum has not been successful in establishing a TCP/IP  session. reqtype is the TCP/IP  API call which  failed, linename is the external name of the line, and xx and ddd are respectively the hexadecimal and decimal representations of the TCP/IP error code. This message can appear several times, as VIRTEL retries periodically to obtain the connection.
Action
    For an explanation of the error codes, refer to Appendix B of the IBM manual z/OS Communications Server: IP Sockets Application Programming Interface Guide and Reference. For VSE, refer to “ERRNO values” in chapter 8 of the IBM manual TCP/IP for VSE/ESA IBM Program Setup and Supplementary Information.
    The following codes are commonly encountered:
