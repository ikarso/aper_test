# aper_test

$ cd SOME_DIRECTORY
$ mkdir code
$ cd code
$ /path/to/asn1c -gen-PER -pdu=Message ../def.asn
$ make -f Makefile.am.sample
$ ./progname -oaper -ixer ../data1.asn.xml > ../data1.asn.aper
$ ./progname -iaper ../data1.asn.aper
$ cat ../data1.asn.xml

hopefully it is the same result :)
