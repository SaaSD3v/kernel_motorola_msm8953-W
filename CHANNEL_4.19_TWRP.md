# Moto G7 Play (channel) 4.19 TWRP bring-up

Base: `4.19.325-WIP`.

- Recovery defconfig: `vendor/channel_recovery_defconfig`
- Channel DTB/DTBO set ported into the 4.19 vendor DT tree
- Himax MMI touchscreen driver ported for recovery input
- DroidSpaces cgroup-v1 and namespace support enabled
- Legacy cgroup-v1 `noprefix` enabled for DroidSpaces

The older SDM632 kernel tree is not modified and is not the source of this 4.19 branch.
