# CANmeleon Hardware — USB-CAN / CAN FD 开源硬件

[English](README.md) · [简体中文](README.zh-CN.md)

CANmeleon Hardware 汇集 USB-CAN/CAN FD 开源硬件设计、板卡资料与社区贡献，面向开发者、硬件厂商和芯片平台，服务汽车、工业、机器人、船舶和自动化等应用。项目采用厂商中立的生态定位。

**硬件资料正在整理。** 各板卡的设计文件、修订版本和发布下载将在本仓库逐项提供。

[提出硬件项目](https://github.com/CANmeleon/canmeleon-hardware/issues/new?template=hardware_project.md) · [参与贡献](CONTRIBUTING.md#中文) · [固件目录](https://github.com/CANmeleon/canmeleon-usb-can-firmware/blob/main/README.zh-CN.md) · [CANmeleon 生态](https://github.com/CANmeleon/.github/blob/main/profile/README.zh-CN.md)

## 硬件与固件如何配合

硬件决定 USB 接口、物理 CAN 通道、收发器、隔离和连接器。固件移植决定电脑端驱动、API 与设备功能。具备相应存储和固件管理能力的设备，可以切换适用的固件系列，每次运行一种。

可贡献的资料包括原理图、PCB 源文件、BOM、结构文件、装配说明、引脚分配和板卡集成指南。每个硬件项目分别说明板卡修订、MCU、时钟、USB 接口、CAN/CAN FD 通道和适用固件。

## 固件选择

| 固件类别 | 用途 |
| --- | --- |
| 项目维护固件 | 由项目维护方提供，作为 CANmeleon 固件生态的一部分维护设备功能。 |
| 开放接口固件 | 通过公开接口或社区软件生态接入。 |
| OEM / 客户固件 | 为设备制造商提供产品专用功能、名称和配置。 |
| 兼容固件 | 与指定电脑端驱动、API 或软件工作流互操作。 |

按完整板卡型号及修订选择固件包。新板卡可提交硬件信息与所需电脑端接口，申请固件移植。

- [CANmeleon 固件目录与下载](https://github.com/CANmeleon/canmeleon-usb-can-firmware/blob/main/README.zh-CN.md)
- [设备管理器](https://github.com/CANmeleon/canmeleon-device-manager/blob/main/README.zh-CN.md)：为支持设备安装、切换和恢复固件
- [开源板卡固件适配申请](https://github.com/CANmeleon/canmeleon-usb-can-firmware/issues/new?template=open_hardware_adaptation.md)，可在申请中说明是否参与免费适配计划

## 参与项目

通过[硬件 Issues](https://github.com/CANmeleon/canmeleon-hardware/issues)提出设计建议、板卡问题和文档改进，附项目链接、板卡修订及相关设计文件。固件功能与移植需求提交到固件仓库。

商业软件/固件集成、芯片平台移植维护及定制固件开发，请联系 [len2slaw@foxmail.com](mailto:len2slaw@foxmail.com)。

## 许可证

仓库原创资料采用 [CERN-OHL-P-2.0](LICENSE)，单独注明其他许可证的组件除外。贡献或复用文件时保留对应组件的许可证与署名。固件包采用其各自的许可和获取条件。
