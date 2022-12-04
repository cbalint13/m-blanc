<img src="docs/images/MBLANC-LOGO.png" width="200"/>

**m**ini **B**oard **LA**b a**n**d **C**ompanion

![DIAG](docs/images/MBLANC-DIAG.png)

## Description

  With the rising of high quality opensource tools for FPGAs new opportunities are emerging to discover and build better digital architectures.
  This board is intended to explore & research the world of modern digital systems that requires large memory bus and high-speed peripherials.

## Specs:

* Large **xc7k420t** **FPGA** design space
* Two **DDR3 SO-DIMM** sockets having **128 (2 x 64) bits** wide access
* USB3 **5Gbps/s** data access over **x32** wide independent FIFO
* USB2 outband (same usb port) permanent **JTAG** and **UART** independent access
* Two  **M.2** (M-key), 4 x SERDes lanes each, PCIe & SATA mappable
* Four **QSFP** sockets 4 x SERDes lanes each, with up to 10Gb/s line rates

Can be used in any USB port right from the tips of fingers, no cables, no wires but full control.

|               TOP                   |               BOTTOM                   |
| ----------------------------------- | -------------------------------------- |
|![TOP](docs/images/MBLANC-3D-TOP.png)|![BOTTOM](docs/images/MBLANC-3D-BOTTOM.png)|

## Progress:

* ```17-Aug-2021``` Initial design and PCB prototype is done.
* ```22-Nov-2022``` Updated design having first PCB samples.

## Project files

* Open Source Hardware <img src="docs/images/OSHW-LOGO.png" width="20"/>
* Check [schematic](hardware/m-BLANC-v0_3.pdf) available as quick readable document.
* See the [design files](hardware) available for Altium ®, CircuitMaker ®, KiCAD and Gerber format.


## PCB views

| Layer    | Desc |             Image                | Layer    | Desc |              Image               |
| -------- | ---- | -------------------------------- | -------- | ---- | -------------------------------- |
|**Top**   |Signal|![GTL](docs/images/layers/GTL.png)|**Inner1**|GND   |![G1](docs/images/layers/G1.png)  |
|**Inner2**|Signal|![G2](docs/images/layers/G2.png)  |**Inner3**|Power |![G3](docs/images/layers/G3.png)  |
|**Inner4**|GND   |![G4](docs/images/layers/G4.png)  |**Bottom**|Signal|![GBL](docs/images/layers/GBL.png)|
