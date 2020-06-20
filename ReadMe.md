# Woz - Apple II and IIe emulator for RISC OS

## Introduction
Originally developed by Benoit Gilon for the Acorn Archimedes, this emulator can run Apple's II and IIe ROM and DOS 3.3/ProDOS applications etc.

This is the port from the old RISC OS 3 to the modern RISC OS 5.xy and fully 32bit.

### Some notes for general users
The emulator comes without Apple's ROMs and OS, so to have it fully working on your RISC OS ARM system you need to find a copy of both and put them in the directory called Boot.

The ROM file should be called ROM2E and the OS floppy disk images should be called Floppy1 (and eventually Floppy2 if you have two floppies images).

### Porting status
I converted the C sources from old Acorn ANSI C release 3 to modern ROOL DDE ANSI C and also fixed few bugs found so ffar and added the Boot location where to put your ROM and floppy images to make it easier for the user to use Woz.

I still need to convert the ARM Assembly code, which was designed for ARMv2 and fully 26bit. So the Emulator is not yet completed and it won't fully work on modern RISC OS systems (yet).

So please be patient and if you want to help me then please feel free to help.


## Build
git clone on a Linux system, share the directory via Samba, access it on RISC via OmniClient and double click on BuildDDE TaskObey in !Woz directory.

Make sure you have ROOL DDE installed and !SetPaths seen/ran by the Filer before attempting to build.


## Important note
This port is dedicated to the work Benoit did on this emulator back in the days and to his memory, RIP and thanks for this software and for making it on RISC OS.



Thanks for your help and support!
- Paolo

