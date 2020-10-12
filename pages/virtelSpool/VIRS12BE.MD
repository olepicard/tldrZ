[VIRS12BE SCENARIO REQUIRES HEADER 'headername' NOT FOUND IN TCT : ABORTING](https://virtel.readthedocs.io/en/latest/manuals/virtel/Virtel459MG/messages.html?highlight=VIRS12BE#VIRS12BE)

`Module`
- VIR0S12

`Meaning`
- A COPY$ SYSTEM-TO-VARIABLE instruction in a scenario is attempting to obtain the value of the HTTP header headername but the name was not declared in the VIRTCT. A subsequent VIRS129E instruction shows the name of the scenario and the location of the instruction in error.

`Action`
- Add headername to the HTHEADR parameter of the VIRTCT.
