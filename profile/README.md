# Microcontroller Common Components.

Open-source libraries and resources for low-level hardware development.

The organization maintains hardware definition libraries, technical documentation, datasheets and supporting tools for microcontrollers, microprocessors and embedded systems.

> [!NOTE]
> **MCC** is a learning project focused on C++ and low-level hardware development, progressing from hardware definitions to high-level abstractions. It explores peripheral interfaces, software architecture, and compatibility across different microcontroller families and architectures.

## Repositories

### Hardware Definitions

Modular, header-only C++ definitions for specific microcontrollers and microprocessors.

| Repository | Description | Documentation |
| --- | --- | --- |
| [ATmega328P](https://github.com/mcc-embedded/atmega328p) | Hardware definitions for the ATmega328P. | [API docs](https://mcc-embedded.github.io/atmega328p/) |
| [ATmega2560](https://github.com/mcc-embedded/atmega2560) | Hardware definitions for the ATmega2560. | [API docs](https://mcc-embedded.github.io/atmega2560/) |

### Adapter Interfaces

Hardware-independent interfaces for MCU peripheral adapters.

| Repository | Description | Documentation |
| --- | --- | --- |
| [Adapter](https://github.com/mcc-embedded/adapter) | Standardized interfaces for common microcontroller peripherals. | [API docs](https://mcc-embedded.github.io/adapter/) |

### Resources

Technical resources supporting hardware development.

| Repository | Description |
| --- | --- |
| [Datasheets](https://github.com/mcc-embedded/datasheets) | Official datasheets for components and devices used in MCC projects. |

## Architecture

MCC separates hardware definitions, reusable adapter contracts, device-specific implementations, and peripheral libraries.

[Architecture Overview](https://github.com/mcc-embedded/.github/blob/main/docs/architecture.md)
