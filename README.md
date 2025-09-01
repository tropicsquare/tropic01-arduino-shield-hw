# TROPIC01 Arduino Shield

This repository contains the design files for the TROPIC01 development shield, designed for the Arduino form factor. Each folder corresponds to a specific PCB revision.

### About TROPIC01

For more information about the TROPIC01 secure element, please see the official documentation:

*   [TROPIC01 Datasheet](https://github.com/tropicsquare/tropic01/tree/main/doc/datasheet)
*   [TROPIC01 Website](https://www.tropicsquare.com/tropic01)

# Arduino Shield's Versions

Following table shows all versions of distributed shields.

| hw revision    | Picture                                                                                                            |
|----------------|----------------------------------------|
| 1401           |  [Top](./TS1401_design/img/top.png)    |

# Getting Started

To interact with the TROPIC01 chip on STM32-based systems we provide the [`libtropic-stm32`](https://github.com/tropicsquare/libtropic-stm32) repository, containing integration examples of our platform-independent SDK, [`libtropic`](https://github.com/tropicsquare/libtropic).

 > [!IMPORTANT]
 > Before you start with various examples, we strongly recommend to do two things first:
 > * Read CHIP ID and TROPIC01's firmware versions and **save printed output for future reference**
 > * Update TROPIC01's both internal firmware to latest version.

In [`libtropic-stm32`](https://github.com/tropicsquare/libtropic-stm32) repository, you can find specifice instruction for both operations based on hardware you use.
