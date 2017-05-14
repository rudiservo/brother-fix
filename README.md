# brother-fix
Fixing brother printing offset top marging (margin cut)


The issue is that brother drivers may not work well with cups

in this case the top hearder/margin of the papers seems always cut, this is true for A4 documents

what solves the issue is to change de default papertype to A4

to do this you can simply use the brother config comand

```
# brprintconf_dcp150c -pt A4
```

or 
```
# nano /usr/local/Brother/Printer/dcp150c/inf/brdcp150crc
```
and change the papertype


this is for the DCP105C the comand might be different if you have any other brother printer
