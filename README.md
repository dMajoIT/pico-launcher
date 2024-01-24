# pico-launcher
Bootloader firmware flasher / launcher for MURMULATOR devboard

# How to use
Copy all your pico firmwares to SD card, then reboot PICO holding down SELECT on Gamepad or DELETE on keyboard

# Compiling
To compile it by yourself you should copy ```boot2\exit_from_boot2.S``` from repository to your pico SDK ```pico-sdk\src\rp2_common\boot_stage2\asminclude\boot2_helpers\exit_from_boot2.S```
