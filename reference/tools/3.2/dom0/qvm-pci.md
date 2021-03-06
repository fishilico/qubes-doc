---
layout: doc
title: qvm-pci
permalink: /doc/tools/3.2/dom0/qvm-pci/
redirect_from:
- /doc/dom0-tools/qvm-pci/
- /en/doc/dom0-tools/qvm-pci/
- /doc/Dom0Tools/QvmPci/
- /wiki/Dom0Tools/QvmPci/
---

```
=======
qvm-pci
=======

NAME
====
qvm-pci - list/set VM PCI devices

SYNOPSIS
========
| qvm-pci -l [options] <vm-name>
| qvm-pci -a [options] <vm-name> <device>
| qvm-pci -d [options] <vm-name> <device>
 
OPTIONS
=======
-h, --help
    Show this help message and exit
-l, --list
    List VM PCI devices    
-a, --add
    Add a PCI device to specified VM
-C, --add-class
    Add all devices of given class:
        net - network interfaces,
        usb - USB controllers
-d, --delete
    Remove a PCI device from specified VM
--offline-mode
    Offline mode

AUTHORS
=======
| Joanna Rutkowska <joanna at invisiblethingslab dot com>
| Rafal Wojtczuk <rafal at invisiblethingslab dot com>
| Marek Marczykowski <marmarek at invisiblethingslab dot com>
```

-----

**Note:** The Markdown source of this page in [`qubes-doc`] was generated by
running the [`update-manpages`] script on `qubes-core-admin/doc/qvm-tools/`.
If you wish to update the contents of this page as it appears on the Qubes OS
website, please submit a pull request to change the appropriate file in
`qubes-core-admin/doc/qvm-tools/`. Do not attempt to change the Markdown source
of this page in [`qubes-doc`] directly. All direct changes to the Markdown file will be
overwritten the next time this page is regenerated.

[`qubes-doc`]: https://github.com/QubesOS/qubes-doc/
[`update-manpages`]: https://github.com/QubesOS/qubesos.github.io/blob/master/_utils/update-manpages

