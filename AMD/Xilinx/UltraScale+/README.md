# AMD Xilinx UltraScale+ Compute Modules
The goal of this project is to make a compute module that supplies and maximizes all necessary external hardware to make a SOM.

|   | Requirement Title | Description |
| - | ----------------- | ----------- |
| 1 | Supply Voltage    | The modlue shall recieve a supply voltage of 5V and step it down to the required votages (3.0V - 3.6V and/or 1.5V - 1.8V) for the onboard components. |
| 2 | RAM               | The module shall maximize ammount of RAM listed in the datasheet for the SOC. |
| 3 | Storage           | The module shall maximize the ammount of external flash and/or dedicated eMMC (not including SD card interfaces although SD cards may be added to the module). |
| 4 | External I/O      | The module shall break out as much of the external periphrials (PCIe, Ethernet, USB, SATA, Display, SDIO, CAN, UART, SPI, I2C, etc...) and I/O as possible. |
