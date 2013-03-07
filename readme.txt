LPC11Uxx Mini
----------------------------------------------------------------------------------

This is a basic breakout board for the NXP LPC11U24 ARM Cortex-M0 microcontroller 
with usb. It has a similar pinout to an Arduino Mini. However, the form factor of 
the Proto1 board is 0.1" wider than an Arduino Mini.

The MCP1252 vreg accepts from 2.5V to 5.5V for running off the RAW pin when usb is 
not connected. When usb is connected the RAW pin provides access to the 'raw' 5V 
usb power. The vreg provides 120mA of 3.3V to run the mcu and some low power 
accessories connected to the VCC pin.

Features:

* program via usb msc (i.e. drag'n'drop new rom to update code)
* on board 3.3V buck/boost voltage regulator
* 22 digital gpio pins including uart, spi, i2c and 8 adc pins
* power indication led and user led (user led is connected to gpio pin D9)
* reset button and isp/user button (isp button is held at boot to enter 
        programming mode and otherwise may be used by user code)

