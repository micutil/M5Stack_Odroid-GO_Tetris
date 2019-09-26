# Tetris for Odroid-GO (& M5Stack)

<img src="tetris_og.jpg">

### Modified by Micutil

- Refered source code: [TETRIS with M5STACK by macsbug](https://macsbug.wordpress.com/2018/01/20/tetris-with-m5stack/)
- Refered source code: [esp32\_ILI9328\_Tetris by MhageGH](https://github.com/MhageGH/esp32_ILI9328_Tetris)
- Modified the sketch for Odroid-GO ([using ESP32-Chimera-Core](https://github.com/tobozo/ESP32-Chimera-Core)).

### Copy the built binnary progurams to microSD

- Copy the files in the microSD folder to the root of microSD.
- Set the microSD into the M5Stack / Odroid-GO
- Select and launche the program with LovyanLauncher.

### Programs
- in M5_Gamebin ... 4M minimal SPIFFS partition scheme
- in MD_Gamebin ... 4M default partition scheme
- in MF_Gamebin ... Fire defaut partition scheme
- in OG_Gamebin ... Arduino program for Odroid-GO
- in odroid/firmwares ... fw file for Odroid-GO


### Control with Odroid-GO

- A button: start game.
- A/B button: rotate lockwisec or counterclockwise.
- Left/right key: move block to left or right.


