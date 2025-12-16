# Smiski Keyboard

The Smiski keyboard is a 4-key macropad with 2 SK6812MINI LEDS, and uses QMK firmware

# Features
- Custom-designed 3D printed smiski case
- 2 SK6812MINI LEDS that diffuse under the case
- 4 keys

# CAD Model
<img width="1027" height="836" alt="image" src="https://github.com/user-attachments/assets/a9d5ecb8-4cb0-478e-b74a-a0612cd45b5f" />
Everything fits with 4 M4x16mm screws.
It has 2 separate 3D printed pieces. One for the case top that sits on top of the PCB, and one for the case base.

# PCB My PCB was made using KiCAD
# **schematic** <img width="894" height="884" alt="image" src="https://github.com/user-attachments/assets/3aca0bad-1217-4122-8fb0-730246aa973a" />
# **pcb** <img width="673" height="913" alt="image" src="https://github.com/user-attachments/assets/1fedb594-3a0f-4036-b040-1cc23823a886" />

**BOM** 
- Seeed XIAO RP2040 x1
- Cherry MX switches x4
- PCB x1 - Blank DSA keycaps x4
- M4x16mm screws x4
- Case (2 separate 3D printed parts) x1


* Keyboard Maintainer: [yashee pasoquen](https://github.com/yasheejp)
* Hardware Supported: *The PCBs, controllers supported*
* Hardware Availability: *Links to where you can find this hardware*

Make example for this keyboard (after setting up your build environment):

    make smiskikeyboard:default

Flashing example for this keyboard:

    make smiskikeyboard:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
