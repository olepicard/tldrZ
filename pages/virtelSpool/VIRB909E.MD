[VIRB909E x-nnnnnn OPEN ERROR, EOJ REQUESTED](https://virtel.readthedocs.io/en/latest/manuals/virtel/Virtel459MG/messages.html?highlight=VIRB909E#VIRB909E)

`Module`
- VIR0B09

`Meaning`
- The batch line with internal name x-nnnnnn was unable to open its input or output file. The batch job terminates with return code 16.

`Action`
- Check the console log for error messages. Check that the job contains DD statements for the input and output files associated with this batch line.
