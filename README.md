# ClamAV Untar XMV representation 

This project contains a nuXmv model of the 0.94 version of the
untar routine in ClamAV, and then a fix to prevent infinite loops.

To run the version that contains an infinite loop (as found
by the LTLSPEC):
```bash
nuXmv untar.smv
```

To run the version that contains a fix for the infinite loop,
preventing the file position from repeatedly going backwards:
```bash
nuXmv untar_fix.smv
```
