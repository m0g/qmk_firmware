```
qmk compile -kb crkbd/r2g -km m0g -e AVR_CFLAGS="-Wno-array-bounds"
qmk flash -kb crkbd/r2g -km m0g -e AVR_CFLAGS="-Wno-array-bounds"
```
