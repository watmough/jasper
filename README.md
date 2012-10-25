Sinclair ZX Spectrum 48 emulator in Java
========================================

This is a fork of original version of Jasper 1.1j by
Adam Davidson and Andrew Pollard. Previously it was available at
http://spectrum.lovely.net/, but currently this website is unavailable.

Also this fork includes a fix allowing screen scaling via a `pixelScale`
variable.

The repo contains the following directories:

* `src` - the sources
* `applet` - original binaries of Jasper 1.1j
* `applet-fixed` - binaries of this fork (including the scaling fix)

To run the emulator:

    cd applet-fixed # or "cd applet"
    appletviewer test.html
