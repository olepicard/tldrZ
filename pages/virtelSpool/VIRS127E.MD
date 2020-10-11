# VIRS127E termid VIRSV SERVICES UNAVAILABLE
`Module`
- VIR0S12
`Meaning`
- A scenario invoked from terminal termid was unable to call a service program using the VIRSV$ macro instruction because the VIRSV service call facility is not available to VIRTEL.
`Action`
- Check that the VIRTCT contains a VIRSV1 parameter. If so, check the VIRTEL log to determine why the VIRSV facility failed to initialise at VIRTEL startup. Refer to message VIR0090E.
