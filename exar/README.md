### [Exar](https://github.com/qitas/Uarts2PCIe) 

XR17V358  PCIe Multiport (8 Channels) Boards

#### method

- unbind pci serial

```
$ ls /sys/bus/pci/drivers/serial/
0000:03:00.0 bind new_id remove_id uevent unbind
$ echo -n "0000:03:00.0" > /sys/bus/pci/drivers/serial/unbind

```
- sudo make
- insmod xr17v358.ko
- ls /dev/ttyRX0

---

### 锻造最美之器

[![sites](qitas/qitas.png)](http://www.qitas.cn)
