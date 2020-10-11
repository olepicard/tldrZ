# VIRHT58E linename IS NOT AN OUTPUT LINE: CANNOT CONNECT termid
`Module`
- VIRHTTP
`Meaning`
- A scenario invoked by terminal termid has attempted to make an outbound HTTP request via the HTTP line whose external name is linename, but the line definition does not permit outbound calls.
`Action`
- Modify the definition of line linename setting the “Possible calls” field to 2 or 3.
