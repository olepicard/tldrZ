# VIRU121E termid FILE UPLOAD FAILED : ENTRY POINT 'epname' DIRECTORY 'dirname' FILE 'filename’ USER 'username’
`Module`
- VIR0U12
`Meaning`
- A request by user username to upload the file filename into the directory dirname at VIRTEL entry point epname failed.
`Action`
- Check, if necessary, that the user has successfully installed a cookie (see “Uploading pages via HTML secured by cookie” in the VIRTEL Web Access Guide). Check the definition of entry point epname. Check (using F6 in the VIRTEL configuration menu) that the directory has permissions “Copy to”, “Copy from”, and “Delete” all marked with “X”. Check that the DD name specified in the directory definition is included in the VIRTEL started task JCL.
