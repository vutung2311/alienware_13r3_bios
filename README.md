Modified BIOS of Alienware 13 R3

- Use PEI volume of version 1.1.6 to exploit BootGuard bug in order to have customized BIOS
- Use DXE volume of version 1.5.0 for latest bug fixes
- Remove Computrace related modules
- Use microcode patch cpu906E9_plat2A_ver0000009A_2018-07-16_PRD_8F717636
- Use original EC image from 1.1.9
- Disable Ipv4 PXE Support and Ipv6 PXE Support
- Enable Voltage Optimization
- Enable Intel Speed Shift Technology
- Disable CFG Lock
- Disable both RTC and BIOS Lock
- Change Firmware Configuration of Platform Settings to Production
- Change ME State of PCH-FW Configuration to Disable
- Change VR Current Limit of Core/IA VR Settings from 440 to 200
- Using latest ME firmware v11.8.60.3561
- Config for ME alternative mode.
- Set Turbo Boost clock override to 36/34/30/28