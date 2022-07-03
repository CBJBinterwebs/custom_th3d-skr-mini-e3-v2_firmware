# custom_th3d-skr-mini-e3-v2_firmware

Ender 3 Max firmware using SKR Mini E3 V2 board<br/>

This is modified version from here:  https://www.th3dstudio.com/hc/downloads/unified-2-firmware/creality/skr-e3-boards/creality-ender-3-max-firmware-skr-e3-mini-v1-v1-2-v2-board/ <br/>

This is for Ender 3 Max with SKR Mini E3 V2 board with touch-sensor (i.e. BLTouch), TFT35 E3 V3.0 screen.  I have enabled linear advance and it is set to zero by default.  Also enabled is filament runout.  I have dual-z but this board has the z-drivers in-line so the 2 motors cannot be controlled separately, that is why G34 dual-z auto-align is disabled.<br/>

I found that using touch-sensor as z-endstop works best, so that is how the firmware is configured.<br/>

This firmware allows for classic Marlin UI mode, you just need to hold-down the jog-dial button or long-press on the screen to bring up the UI selection prompt.
