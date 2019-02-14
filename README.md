# Operating-system-on-Nexys4DDR
I have followed the steps from a [tutorial] (https://numato.com/kb/neso-microblaze-linux-run-linux-neso-artix-7-fpga-module/) about how to use Linux on Neso Artix 7 FPGA Module 
in order to run Linux on Microblaze microprocessor of Nexy4DDR Xilinx FPGA.

You can find the VHDL Microblaze based design [here](https://drive.google.com/open?id=1hH_0bFCKllBBNAE0KmEyMKzA5Xz0jvmO) and the built kernel image [here] (https://drive.google.com/open?id=16sisLT27eqf15LptbpqN0mRc0omVqLQd).
After you have connected the FPGA, lunched Xilinx SDK, opened a serial terminal program and connected at 115200 baudrate,
you need to enter the following commands:
*) connect mb mdm
*) dow simpleImage.xilinx
*) con 0x80000000
