[VIRB179E ERROR ON: luname ALLOCATING 64 BITS STORAGE - RETCODE: xxxxxxxx - REASON CODE: xxxxxxxx](https://virtel.readthedocs.io/en/latest/manuals/virtel/Virtel459MG/messages.html?highlight=VIRB179E#VIRB179E)

`Module`
- VIR0B17

`Meaning`
- An memory allocation attempt failed while trying to store a VIRTEL variable above 'above the BAR' (ie in 64 bits storage). The hexadecimal return code and reason code could be researched in the DC2 code in the IBM “z/OS   MVS System Codes” manual or possibly in the IBM IARV64 service documentation in the “MVS Assembler Services Reference” manual. Virtel currently limits the maximum size of a Virtel variable to 2 gigabytes. The maximum amount of 64-bit private virtual memory available to the Virtel address space can be controles by the MEMLIMIT JCL parameter.

`Action`
- Use an appropriate value in the MEMLIMIT JCL parameter.
