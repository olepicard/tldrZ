# VIRHT56I n-xxxxxx CALLER real-ip WAS FORWARDED BY proxy-ip
Module
    VIRHTTP
Meaning
    An HTTP request was received from proxy-ip on the HTTP line whose internal name is n-xxxxxx. The source IP address proxy-ip appears in the “Calling DTE” field of a rule attached to the HTTP line, and the request matches the rule in all other respects. VIRTEL considers the IP address real-ip, which is specified in the “forwarding header” inserted by the proxy, to be the real originating IP address. Refer to “Calling DTE” in the “Rules” chapter of the VIRTEL Configuration Reference manual for further information.
Action
    VIRTEL henceforth treats the call as if it had been received from real-ip instead of from proxy-ip. The real-ip address will be displayed in console messages and recorded in the VIRLOG.
