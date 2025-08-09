<h2> igai: SPI to I²C Bridge IP Core </h2>

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

<p align="center">
  <img src="docs/images/results/igai_logo.png" width=250 alt="Igai IP logo">
</p>

## Introduction

Igai is a compact and efficient **SPI-to-I²C bridge IP core** designed to enable smooth communication between SPI-based controllers and I²C peripherals. Acting as a protocol converter, Igai receives commands and data over the Serial Peripheral Interface (SPI) and translates them into I²C transactions, making it easy to integrate I²C devices into SPI-based systems.

This IP core is particularly useful in embedded designs where an SPI host must control I²C sensors, EEPROMs, displays, or other I²C-compliant components without the need for dedicated I²C hardware in the host system.

Key features of Igai include:
- **Full-Duplex SPI Interface:** Receives and transmits data efficiently over SPI in master or slave mode.
- **Protocol Translation:** Converts SPI commands into standard-compliant I²C read and write operations.
- **Multi-Device I²C Support:** Supports 7-bit addressing for communication with multiple I²C devices on the same bus.
- **Configurable SPI Modes:** Compatible with all four SPI clock polarity (CPOL) and phase (CPHA) settings.
- **I²C Master Mode:** Operates as an I²C bus master to initiate and control transactions.
- **Variable Data Widths:** Flexible data sizes for both SPI and I²C transfers.
- **Low Latency Operation:** Optimized bridging for minimal delay between SPI request and I²C response.
- **Error Handling:** Detects NACK responses, bus contention, and invalid commands.
- **Interrupt Support:** Event-driven notification for completed transactions and error events.

Igai is supplied with a comprehensive verification suite to ensure correct functionality and high reliability across a variety of configurations.  
It is well-suited for both FPGA and ASIC implementations, enabling robust interoperability between SPI and I²C domains.

Refer to the [documentation](docs/) for detailed configuration options, integration steps, and simulation examples.
