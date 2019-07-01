# Code-based-on-ST-boards
Communication beetwen NUCLEO-F401RE and  STM32F3Discovery

STEP:

- Configure in the STM32 Core (NUCLEO-F401RE) the PA10 pin in output
- Set the PC6 pin as input in the STM32F3Discovery
- Connect the two pins of the boards with a wire 

Description:
1. The key of the STM32 Core is used as start / stop.
a) When the blue button is pressed, the LED button will bring up the value of PA10;
b) At the next pressing of the blue button, deactivate the whole (activates the toggle and bring PA10 down);
2. In the STM32F3Discovery whenever PA10 becomes high, increase a global variable ed
make a led rotation (led4, led3, led5, led7, led9, led10, led8, led6, led4)
