# microbit-rock-paper-scissors

An interactive, motion-based Rock-Paper-Scissors game built for the BBC micro:bit (v1). This project is designed for educational workshops and library activities for young learners.

## Features
* **Motion Detection:** Uses the built-in accelerometer (`on shake` event) to trigger a random choice.
* **Randomized Logic:** Generates a random value between 1 and 3 to simulate Rock, Paper, or Scissors.
* **Visual Feedback:** Displays custom LED icons corresponding to each outcome.
* **v1 Hardware Support:** Fully optimized for original micro:bit boards without requiring built-in speakers or touch pins.

## MakeCode Block Diagram
Below is the logic implemented using Microsoft MakeCode blocks:

![MakeCode Blocks](./blocks-code.png)

## How It Works
1. Shake the micro:bit to trigger the game.
2. A random number is generated:
   * **1** = Rock (Solid LED square/box)
   * **2** = Paper (Full LED screen)
   * **3** = Scissors (X icon or custom scissors pattern)
3. The selected icon flashes on the 5x5 LED display.

## How to Deploy
1. Download the `microbit-rock-paper-scissors.hex` file from this repository.
2. Connect your micro:bit to your computer via USB.
3. Drag and drop the `.hex` file onto the micro:bit drive.
