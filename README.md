# Nintendo Switch Gamepad Arduino Library Using TinyUSB

Create Nintendo Switch compatible gamepads using Arduino and TinyUSB. This has
only been tested on RP2040 boards such as the Raspberry Pi Pico using the
[Earle Philhower RP2040 board
package](https://github.com/earlephilhower/arduino-pico).

This may work on other boards supported by the Adafruit TinyUSB library but
no testing has been done.

Install this library by downloading a zip file from this repo. Use the IDE
"Add .zip library" option.

## Dependencies

Use the IDE Library Manager to install the library named "Adafruit TinyUSB
Library".

## Troubleshooting

If the following error message appears when compiling, change the USB Stack to
"Adafruit TinyUSB" as it says in the message.

```
   32 | #error TinyUSB is not selected, please select it in "Tools->Menu->USB Stack"
      |  ^~~~~
```
