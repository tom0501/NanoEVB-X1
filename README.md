# NanoEVB-X1: M.2/NGFF based Xilinx development board

![Image of NanoEVB](./NanoEVB-X1-top.png)

The NanoEVB-X1 is an affordable development board which can be used to evaluate and prototype 
PCI express designs using Xilinx Artix 7 FPGA on Windows or Linux hosts.
The board is designed around the Artix 7 (XC7A50T).

The NanoEVB-X1 is a complete development system in a M.2 (NGFF) 2242 footprint. The JTAG cable
and all necessary power supplies are built in. It will work in the following slots:
 
- M.2 2242 Key A
- M.2 2242 Key E
- Full length mini PCIe via an adapter [like this one](https://www.amazon.com/dp/B01MR76H5F)

## Features
- PCI Express connection to the host via M.2 edge slot
- Built-in JTAG cable works with Vivado and Labtools
- Analog/digital IO
- Spare UART RS232 connection to the FPGA via FT2232


# PicoEVB-X1

![Image of PicoEVB](./PicoEVB-X1-top.png)

The PicoEVB is a smaller version of the NanoEVB, shrunk to fit in a M.2 2230 slot.
The spare uart has been removed to allow the fit into the following slots:

- M.2 2230 Key A
- M.2 2230 Key E
- Full length mini PCIe via an adapter [like this one](https://www.amazon.com/dp/B01MR76H5F)

## Features
- PCI Express connection to the host via M.2 edge slot
- Built-in JTAG cable works with Vivado and Labtools
- Analog/digital IO

## Block Diagram

![Block Diagram](./EVB-block-diagram.png)

Note that the I/O connector pinout is identical for NanoEVB & PicoEVB; they are 
interchangeable- you can even use the same exact bitstream.

## How to get one
[Check us out on Crowd Supply](https://www.crowdsupply.com/rhs-research/nanoevb)


## More information

[Check out the wiki](https://github.com/RHSResearchLLC/NanoEVB-X1/wiki)

or contact info@nanoevb.com




