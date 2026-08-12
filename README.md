# RDX-FORK

Payloads can remain locally in:

```text
/data/ps5_autoloader/
```

`autoload.txt` controls the payload execution sequence.

Example:

```text
!4000
ftpsrv-ps5-0.19.elf
!4000
shadowmountplus.elf
!4000
kstuff.elf
!4000
elf-arsenal.elf
```

The payloads themselves do not need to be downloaded from the web interface.

[RDX-FORK WebKit](https://rdx-sci01.github.io/WebKit/)
