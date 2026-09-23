# Moto G7 Play (channel) 4.19 TWRP bring-up

Base: `4.19.325-WIP`.

This branch is intentionally limited to validating TWRP on the 4.19 kernel first.

- Recovery defconfig: `vendor/channel_recovery_defconfig`
- Channel SDM632 platform selector enabled
- Channel base DTB and Motorola DTBO overlays ported into the 4.19 vendor DT tree
- Himax, Novatek and Ilitek touchscreen support ported for Channel hardware revisions
- Official TWRP 3.5.2_10-0 recovery image is used as the ramdisk/base image by CI
- No DroidSpaces-specific Kconfig flags or cgroup patches are included in this validation branch

DroidSpaces support will be added only after the 4.19 TWRP base is confirmed booting on-device.
