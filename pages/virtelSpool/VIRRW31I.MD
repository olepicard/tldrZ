[VIRRW31I linename REQUEST timestamp1 CORR=correlator TIMEOUT Q=qname](https://virtel.readthedocs.io/en/latest/manuals/virtel/Virtel459MG/messages.html?highlight=VIRRW31I#VIRRW31I)

`Module`
- VIR0RAW

`Meaning`
- VIRTEL has not received a response to a message sent by terminal termname on the line whose external name is linename. The time of the request is timestamp1. The correlator is correlator. The queue name is qname.

`Action`
- Check the message queue manager log to determine why no response was received.
