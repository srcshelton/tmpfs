tmpfs
=====

Mirror segments of a filesystem to a memory-based backing store.

tmpfs is a script written for the OpenRC init system to mirror selected data
from disk to a memory- or NFS- based filesystem (or similar) and to restore the
data on system shutdown.

The primary aim is to extend the lifetime filesystems running from consumer-
grade low-cost flash devices such as USB sticks, MMC/SD cards, or Compact
Flash.

https://github.com/srcshelton/gentoo-ebuilds also contains an ebuild-version of
this script, for easy installation on Gentoo Linux.

tmpfs has been extensively tested on a PC Engines Alix system, Ubiquiti EdgeMAX
routers and several Raspberry Pis.

