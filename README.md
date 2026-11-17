# CANmeleon Hardware — Open USB-CAN & CAN FD Designs

[English](README.md) · [简体中文](README.zh-CN.md)

CANmeleon Hardware brings together open-source USB-CAN/CAN FD hardware designs, board documentation and community contributions. It is part of a vendor-neutral ecosystem for developers, hardware manufacturers and chip platforms working across automotive, industrial, robotics, marine and automation applications.

**Hardware documentation is being organized.** Board-specific design files, revisions and release downloads will be listed here as they become available.

[Propose a hardware project](https://github.com/CANmeleon/canmeleon-hardware/issues/new?template=hardware_project.md) · [Contribute](CONTRIBUTING.md) · [Firmware catalog](https://github.com/CANmeleon/canmeleon-usb-can-firmware) · [CANmeleon ecosystem](https://github.com/CANmeleon)

## Hardware and firmware work together

Hardware defines the USB interface, physical CAN channels, transceivers, isolation and connectors. A firmware port defines the host driver, API and device behavior. Devices with suitable storage and firmware management can switch between applicable firmware families, running one at a time.

Contributions can include schematics, PCB source files, BOMs, mechanical files, assembly information, pin assignments and board integration guides. Each hardware project identifies its board revision, MCU, clocks, USB interface, CAN/CAN FD channels and applicable firmware.

## Firmware choices

| Firmware category | Purpose |
| --- | --- |
| Project-maintained firmware | Device functions maintained as part of the CANmeleon firmware ecosystem. |
| Open-interface firmware | Access through public interfaces or community software ecosystems. |
| OEM / customer firmware | Product-specific functions, naming and configuration for a manufacturer's device. |
| Compatibility firmware | Interoperability with a particular host driver, API or software workflow. |

Choose a firmware package for the exact board and revision. For a new board, submit its hardware information with the required host interface.

- [CANmeleon firmware catalog and downloads](https://github.com/CANmeleon/canmeleon-usb-can-firmware)
- [Device Manager](https://github.com/CANmeleon/canmeleon-device-manager) for supported devices: firmware installation, switching and recovery
- [Open-source board firmware adaptation requests](https://github.com/CANmeleon/canmeleon-usb-can-firmware/issues/new?template=open_hardware_adaptation.md), including requests for the free adaptation program

## Participate

Use [hardware Issues](https://github.com/CANmeleon/canmeleon-hardware/issues) for design proposals, board questions and documentation improvements. Include the project URL, revision and relevant design files. Use the firmware repository for firmware behavior and porting requests.

For commercial software/firmware integration, chip platform porting and maintenance, or custom firmware, contact [len2slaw@foxmail.com](mailto:len2slaw@foxmail.com).

## License

Original repository materials use [CERN-OHL-P-2.0](LICENSE), unless a component states another license. Preserve each component's license and attribution when contributing or reusing its files. Firmware packages carry their own licenses and access terms.
