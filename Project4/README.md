# Code-based-on-ST-boards
SERVO MOTOR CONTROLLED BY TRIMMER/PWM SIGNAL 

-board:NUCLEO-F401RE

Values ​​from the trimmer are converted from ADC Unit. At each detection of the trimmer data, the ADC generates an interrupt. These values ​​allow the variation of the duty cycle. The ADC values ​​will be transmitted through UART to the laptop.



