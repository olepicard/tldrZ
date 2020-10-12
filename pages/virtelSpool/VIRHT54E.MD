# VIRHT54E INVALID REQUEST ON linename ENTRY POINT 'epname' DIRECTORY 'dirname' PAGE 'filename' URL 'url' TRANSACTION 'tranid' CALLER ipaddr:port reason

`Module`
- VIRHTTP

`Meaning`
- VIRTEL received a request on the HTTP line whose external name is linename originating from the browser at IP address ipaddr:port. The browser requested HTML page filename using URL url. Either the directory path dirname does not exist, or there is no transaction named tranid under the entry point epname.

`Action`
- Check that the browser requested the correct URL. Check the definition of the entry point epname. If reason is “missing directory : dirname”, ensure that there is a type 4 transaction with external name dirname. If reason is “rejected transaction : tranid”, ensure that there is a type 1 transaction with external name tranid. See “VIRTEL URL formats” in the VIRTEL Web Access Guide.
