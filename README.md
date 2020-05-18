# step\_fan\_speed

## Description 
Simple PCB to control computer fan speed with a atinny88

The board runs out of the fan 12V, step down to 3.3V with an LDO.

It provides a PWM header in and PWM out. The MCU is able to intercept the
signal of the tachometer and generated a new PWM signal.

## Usage 
The uart is accesible through a two pin headeris. External FTDI bridge is required
if you want to connect it to the computer.

The board is programmed  thorugh ISP with a Tag-connect cable or UART if a
bootloader if it has been previously programmed.

## IO
* 3 DIP switches
* 1 Push button
* 2 LEDs 
* NTC sensor.
* I2C port (As SMD pads)
* PMW in
* PWM out
* UART

