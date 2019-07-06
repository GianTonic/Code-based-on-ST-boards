# Code-based-on-ST-boards
COMMAND FROM UART2

board:NUCLEO-F401RE

Every time a message arrives from the UART, an interrupt is generated to manage the command.

Message format:
PINxy

with:

-x = 1 or 2 (to indicate the first or second pin)

-y = 0 or 1 respectively low or high

-y = Y toggle

In this case PIN1 = PC6, PIN2 = PC7.

