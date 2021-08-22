# DDR3 Memory Controller (FPGA)

This project contains the source code of a memory controller used in SAFARI projects that interfaces with the Xilinx MIG-7 PHY over the DFI interface. It also exposes an AXI4-ish interface (violates the standard) to user hardware.

The project does not work out of the box, you need to instantiate a MIG IP and leave out some of its top level modules and connect it to the controller we provide.

## Contacts

Feel free to send an email to contacts listed below or open an issue on the repo if you have any questions:

- Ataberk Olgun: ataberk.olgun \<at\> inf \<dot\> ethz \<dot\> ch