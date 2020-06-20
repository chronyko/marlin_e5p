# marlin_e5p
Modified Marlin for Creality Ender 5 Plus (Released by Creality)

Note that this is a fork from Kersey Automations Github repo.

This is easiest to compile using the Arduino IDE. You will need to install various libraries as indicated at compile time.

Set the board type to Arduino Mega 2560.

Select export sketch to bianry and you will find the compiled binary in the same directory. You want the Marlin.ino.hex file WITHOUT bootloader. The file can be uploaded using the Creality Slicer tool.

For more info see:
https://p3dt.net/post/2020/05/01/ender-5-plus-firmware-building.html

Note that compiling with VSCode / PlatformIO hasn't worked to date but should be possible.