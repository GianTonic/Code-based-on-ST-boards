# NucleoSTM32F401-and-STM32F3Discovery-communication
Nucleo STM32F401 and STM32F3Discovery using RTOS

- Configure in the STM32 Core (NUCLEO-F401RE) pin PA10 as output
- Set the PC6 pin as input in the STM32F3Discovery
- Connect the two pins of the boards with a wire (see next slide figure)
Description:
1. The key of the STM32 Core is used as start / stop.
a) When the blue button is pressed, activate the toggle of the LED and set the value of PA10 high;
b) At the next press of the blue button, deactivate the whole (turn off the toggle and bring PA10 down);

2. In the STM32F3Discovery whenever PA10 becomes high, increase a global variable ed
make a led rotation (led4, led3, led5, led7, led9, led10, led8, led6, led4)

