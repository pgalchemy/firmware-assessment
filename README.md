# Firmware Assessment

## Objective

Create [Simon](https://en.wikipedia.org/wiki/Simon_(game)) the game.

## What's provided

- (1) ESP32 Devkit-C v4
- (4) LEDs
- (4) Push buttons
- (1) Breadboard
- (-) Wires

## Details

The game should follow this basic outline:

1) Press a button to begin the game
2) Simon lights up a random LED sequence
3) User must mimic the sequence by pressing the push buttons
4) If the user makes a mistake in the sequence, they lose
5) If the user inputs the sequence correctly, they either win or continue the game

You will need to do the following high level things:

1) Install ESP-IDF v4.1
2) Wire up electronics on breadboard
3) Write game
4) Flash game
5) Demonstrate game

Links to relevant documentation are at the bottom of this document.

## Remarks

- Estimated time: 6-8 Hours
- The program should be written in C
- The dev boards provided require a micro-USB cable to flash
- Be creative with the game (e.g. number of rounds, play speed, led animations)
- Feel free to use extra electronic components if you feel compelled
- Be prepared to discuss your code and development process
- Good luck!

## Helpful links

[ESP32 Pinout Guide](https://randomnerdtutorials.com/esp32-pinout-reference-gpios/)

[ESP-IDF Programming Guide](https://docs.espressif.com/projects/esp-idf/en/release-v4.1/index.html)

[GPIO API Reference](https://docs.espressif.com/projects/esp-idf/en/release-v4.1/api-reference/peripherals/gpio.html)

[Miscellaneous System APIs](https://docs.espressif.com/projects/esp-idf/en/release-v4.1/api-reference/system/system.html)

[FreeRTOS Reference](https://docs.espressif.com/projects/esp-idf/en/release-v4.1/api-reference/system/freertos.html)
