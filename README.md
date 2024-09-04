# DIY-Mechanical-Keyboard
A DIY project to make a mechanical keyboard using handwired switches, Arduino Pro Micro and 3d printing.

Resources:
- Keyboard Layout Editor (http://www.keyboard-layout-editor.com/)
- Keyboard Firmware Builder (https://kbfirmware.com/)
- QMK (https://qmk.fm/)

Steps:
1. Create keyboard layout using Keyboard Layout Editor (http://www.keyboard-layout-editor.com/)
2. Import layout to Keyboard Firmware Builder (https://kbfirmware.com/)
3. Setup wiring plan
4. Setup MCU pinout, using 32u4 in this case (see ProMicro16MHzv1.pdf for pinout - prefixed with "P")
5. Create keyboard keymap
6. Export source files
7. Install firmware using QMK (https://qmk.fm/) 
