
FRC Toolchain builder
=====================

Originally cloned from https://bitbucket.org/byteit101/toolchain-builder/downloads

at commit https://bitbucket.org/byteit101/toolchain-builder/commits/5de14e5bbf2c0af64ed671b874e33006b9b47c5a

This repository builds the compiler and related binutils, etc. for the FRC arm architecture that runs on National Instruments hardware.  

The compiler has not yet been released for Ubuntu 16.04 or 16.10, so this repository can be used to build.

Installation guidance
=====================

The compiler that is built for the FRC RoboRIO arm architecture uses gcc-4.9 .  On newer systems, gcc-5 and gcc-6 are likely also installed.  In order to build the gcc-4.9 series, a gcc-4.9 series compiler is recommended.  There may be issues with building using gcc-5 or gcc-6 due to some language standards changes.  It is possible to switch compilers using update-alternatives or similar.

A install-dependencies.sh file will install the necessary support programs and libraries to build the Ubuntu/Debian .deb files.


