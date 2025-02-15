# Streamdeck
3D printed USB streamdeck

This project is a remake of https://www.thingiverse.com/thing:4186055 based on an Arduino Pro Micro and HID capabilities

My current keys assignment (under Linux) is the following: it can be fully customized by printing the relevant keycaps and configuring the shortcuts using your preferred OS.

```
1       mute mic
2       mute speaker
3       audio pause
4       audio prev
5       audio next
6       volume down
7       volume up
8       screen capture
9       window capture
10      spectacle
11      keyboard layout switcher
12      custom key 1
13      custom key 2
14      run konsole
15      screensaver
```

Hardware BoM is
- Arduino pro micro (https://www.aliexpress.com/item/32989454699.html)
- 0.96" 128x32 pixels OLED display (https://www.aliexpress.com/item/32672229793.html)
- 3 and 4 pins JST XH2.54 cables and terminals (https://www.aliexpress.com/item/32968520253.html and https://www.aliexpress.com/item/4000801004876.html)
- 4x M3x8mm screws
- Micro USB to USB cable
- Cherry MX switches (https://www.aliexpress.com/item/4000406734661.html)

STL files should be printed using 0.1mm layer height and 3 walls

On thingiverse: https://www.thingiverse.com/thing:4737914

Libraries needed to compile the sketch are:
- https://www.arduino.cc/reference/en/libraries/adafruit-ssd1306/
- https://www.arduino.cc/reference/en/libraries/adafruit-gfx-library/
- https://www.arduino.cc/reference/en/libraries/keypad/

Important notes:
- Stream_deck_body.stl, keys_plate_v6.stl and SSD1306_lid.stl must be printed for the final assembly as in the photographs.
- Case Remix v5.stl is for macro_keypad_top_large_PCB.stl, I didn't try to print it as I don't have this specific keypad. If you happen to print it, please let me know if it fits well.

# Images

<img src="./images/1.png"/>

<img src="./images/IMG_0758.JPG"/>

<img src="./images/schematics.png"/>
