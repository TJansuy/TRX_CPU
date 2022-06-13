# TRX_CPU
Was curious to play with my FPGA a bit, and decided to try to build a very simple processor that could move memory values around a small RAM bank.

## TRX_CPU.bdf
![Visual representation of the block design file for the TRX_CPU](TRX_CPU.png)

## TRX_RAM_4Byte
![The 2 implemented selectors wired up to 4 memory units](TRX_RAM_4Byte.png)

## Select4.bdf
![A simple Select circuit to enable and choose a single output](Select4.png)

## 8BitMem.bdf
![A simple 8-bit memory unit using Clocked D-Latches](8BitMem.png)
