# Introduction #

Flashrom is a utility for identifying, reading, writing, verifying and erasing flash chips. It's often used to flash BIOS/EFI/coreboot/firmware images.


# Details #

  * Supports more than 195 flash chips, 75 chipsets, 130 mainboards, and 17 devices (PCI or USB) which can be used as external programmers.

  * Supports parallel, LPC, FWH and SPI flash interfaces and various chip packages (DIP32, PLCC32, DIP8, SO8/SOIC8, TSOP32, TSOP40, TSOP48, and more)

  * No instant reboot needed. Reflash your chip in a running system, verify it, be happy. The new firmware will be present next time you boot.

  * Crossflashing and hotflashing is possible as long as the flash chips are electrically and logically compatible (same protocol). Great for recovery.

  * Scriptability. Reflash a whole pool of identical machines at the same time from the command line. It is recommended to check flashrom output and error codes.

  * Speed. flashrom is often much faster than most vendor flash tools.

  * Portability. Supports Linux, FreeBSD, DragonFly BSD, Solaris, Mac OS X, and other Unix-like OSes.


http://www.flashrom.org/Flashrom