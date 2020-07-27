# FireBox: Outputs and Sensors

FireBox has a 20-pin expansion header, with 18 pins able to act as either outputs or sensors. 

!!! Note
    FireBox has 3.3v tolerant I/O pins only! Attempting to use FireBox with 5V devices will result in the destruction of those I/O pins, or worse, the complete destruction of the FireBox device.

Input and output pins can be used in one of two ways. The first method involves using the DCC++ commands through the serial monitor

TODO: Add instructions on how to use DCC++ commands.

The second method involves hard-coding the inputs and outputs from within the firmware to perform certain functions. This allows greater control over the I/O, and extra peripherals such as timers and serial ports may be used. Below is a table of the different available pins and peripherals.

TODO: Add table