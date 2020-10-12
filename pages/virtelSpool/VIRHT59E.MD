# VIRHT59E LINE linename IS NOT OPEN: CANNOT CONNECT termid

`Module`
- VIRHTTP

`Meaning`
- A scenario invoked by terminal termid has attempted to make an outbound HTTP request via the HTTP line whose external name is linename, but the line is stopped.

`Action`
- Start the line by entering the VIRTEL command: line=linename,S
