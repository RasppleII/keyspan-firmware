# keyspan-firmware for Raspple II

This package contains the firmware for Keyspan USB-serial adapters popular
amongst Mac users once Apple transitioned to USB.  The devices are no longer
made today, but many Apple // users are likely to have one kicking around as
they worked pretty well on Macs and PCs of that era, and about half of them
had the familiar Apple-style mini-DIN8 serial connector.

The firmware files themselves come from linux-firmware.  Debian provides
linux-firmware in two packages.  The firmware files which are free software
as defined by the Debian Free Software Guidelines (DFSG) are in the Debian
linux-firmware package.  Those that aren't go into linux-firmware-nonfree.

The Keyspan firmware most decidedly belongs in the latter camp.  However the
Copyright on the keyspan firmware states that the Keyspan firmware may be
distributed with an open source kernel or operating system.  Debian quite
explicitly declares its non-free archive to be NOT part of Debian itself,
despite living in the same package archive.  As such, a strict and pedantic
reading of the license forbids Debian to distribute the files.  Hoisted by
their own petard on that one!

Raspple II considers our whole archive to be part of the Raspple II
operating system, which is a light derivative of Debian and Raspbian
depending on your chosen platform.  We're sure InnoSys would agree, if they
still existed.  They were bought by Tripp-Lite who no longer manufactures
any of the old InnoSys/Keyspan products anyway.
