# freebsd-13-entropyfix

Get the full CDROM with installer on Sourceforge:
https://sourceforge.net/projects/freebsd-12-r328126/

CDROM ISO: 
https://sourceforge.net/projects/freebsd-12-r328126/

boot directory copy from the cdrom of working entropy on modern notebook, i.e. FreeBSD 12.0-current freebsd 12.0-current #0 r328126 thu jan 18 18:13:19 utc 2018 boot@relengen3.nyi.freebsd.org /usr/obj/usr/src/i386.i386/sys/eneric i386


The best fix is to use : 
    pkg static 

You're supposed to run pkg-static install -f pkg as pkg output suggests.



