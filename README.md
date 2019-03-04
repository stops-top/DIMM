# [UART<->PCIE](https://github.com/qitas/UART-PCIE) 

#### qitas@qitas.cn

## [描述](https://github.com/qitas/UART-PCIE/wiki) 

通过转换芯片实现多串口和PCIE间的转换，实现串口通信的扩展驱动

## [平台&资源](qitas/)

### [WCH厂商](wch/)

#### [CH384方案](http://www.wch.cn/products/CH384.html)

CH384 是PCI-Express总线的四串口及打印口芯片，包含四个兼容16C550或者16C750 的异步串口和一个EPP/ECP 增强型双向并口，并且还可以外加CH438 芯片扩展最多达24 个串口。异步串口提供收发独立的256 字节FIFO 缓冲器，支持IrDA红外编解码，支持最高8Mbps的通讯波特率，可以用于PCIE 总线的RS232串口扩展、带自动硬件速率控制的PCIE 高速串口、串口组网、RS485通讯、IrDA通讯、并口/打印口扩展等。

### [Exar厂商](exar/)

#### [XR17V358方案](https://www.exar.com/product/interface/uarts/pcie-uarts/xr17v358)

The XR17V358 (V358) is a single chip 8-channel PCI Express (PCIe) UART (Universal Asynchronous Receiver and Transmitter), optimized for higher performance and lower power. The V358 serves as a single lane PCIe bridge to 8 independent enhanced 16550 compatible UARTs. The V358 is compliant to PCIe 2.0 Gen 1 (2.5GT/s).

In addition to the UART channels, the V358 has 16 multi-purpose I/Os (MPIOs), a 16-bit general purpose counter/timer and a global interrupt status register to optimize interrupt servicing.




---

### 锻造最美之器

[![sites](qitas/qitas.png)](http://www.qitas.cn)
