# Compilation


```
gcc nl_poll.c  -o nl_poll -O2 -Wall -W -Werror  -pedantic
```

# Tests


```
./nl_poll 

NETLINK => [change@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6/2-1.6:1.0/host7/target7:0:0/7:0:0:0/block/sdc]
NETLINK => [remove@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6/2-1.6:1.0/host7/target7:0:0/7:0:0:0/bsg/7:0:0:0]
NETLINK => [remove@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6/2-1.6:1.0/host7/target7:0:0/7:0:0:0/scsi_generic/sg2]
NETLINK => [remove@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6/2-1.6:1.0/host7/target7:0:0/7:0:0:0/scsi_device/7:0:0:0]
NETLINK => [remove@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6/2-1.6:1.0/host7/target7:0:0/7:0:0:0/scsi_disk/7:0:0:0]
NETLINK => [remove@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6/2-1.6:1.0/host7/target7:0:0/7:0:0:0/block/sdc]
NETLINK => [remove@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6/2-1.6:1.0/host7/target7:0:0/7:0:0:0]
NETLINK => [remove@/devices/virtual/bdi/8:32]
NETLINK => [remove@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6/2-1.6:1.0/host7/target7:0:0]
NETLINK => [remove@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6/2-1.6:1.0/host7/scsi_host/host7]
NETLINK => [remove@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6/2-1.6:1.0/host7]
NETLINK => [remove@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6/2-1.6:1.0]
NETLINK => [remove@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6]


NETLINK => [add@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6]
NETLINK => [add@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6/2-1.6:1.0]
NETLINK => [add@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6/2-1.6:1.0/host8]
NETLINK => [add@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6/2-1.6:1.0/host8/scsi_host/host8]
NETLINK => [add@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6/2-1.6:1.0/host8/target8:0:0]
NETLINK => [add@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6/2-1.6:1.0/host8/target8:0:0/8:0:0:0]
NETLINK => [add@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6/2-1.6:1.0/host8/target8:0:0/8:0:0:0/scsi_disk/8:0:0:0]
NETLINK => [add@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6/2-1.6:1.0/host8/target8:0:0/8:0:0:0/scsi_device/8:0:0:0]
NETLINK => [add@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6/2-1.6:1.0/host8/target8:0:0/8:0:0:0/scsi_generic/sg2]
NETLINK => [add@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6/2-1.6:1.0/host8/target8:0:0/8:0:0:0/bsg/8:0:0:0]
NETLINK => [add@/devices/virtual/bdi/8:32]
NETLINK => [add@/devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.6/2-1.6:1.0/host8/target8:0:0/8:0:0:0/block/sdc]
NETLINK => [add@/kernel/slab/nf_conntrack_98]

```

