[VIRQ924E linename OBJECT socknum REQ reqtype COMPLETION CODE ccc REASON CODE xx (ddd) MQM mqmname | linename PARAM queuename](https://virtel.readthedocs.io/en/latest/manuals/virtel/Virtel459MG/messages.html?highlight=VIRQ924E#VIRQ924E)

`Module`
- VIR0Q09

`Meaning`
- A message queue manager request of type reqtype for the line whose external name is linename was not successful. mqmname is the name of the message queue manager, ccc is the message queue manager completion code, and xx and ddd are respectively the hexadecimal and decimal reason codes. queuename is the name of the message queue, if any, associated with the error.

`Action`
- For an explanation of the error codes, refer to Appendix A of the IBM manual MQSeries Application Programming Reference.
