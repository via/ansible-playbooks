The ipxe.kpxe image is ipxe built with two custom options:
- CONSOLE_SERIAL
- A integrated ipxe script:
```
#!ipxe
set user-class iPXEs
autoboot
```

This allows the dhcp config to distinguish between our custom build that
enables a serial console (for kvm) from one potentially supplied as part
of a qemu instance.
