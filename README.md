# rosco_ll_filetest
Test low level SPI routines for the SD Card on the rosco_m68k SBC

Compile with:
```shell
     ROSCO_M68K_DIR=~/rosco_m68k make EXTRA_CFLAGS=-DROSCO=1
```

# *** THIS WILL DESTROY THE FAT32 FORMATTING ON YOUR SD DRIVE ***

So use a blank SD Card or one you dont care about ..