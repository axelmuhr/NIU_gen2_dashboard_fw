# NIU 2nd generation dashboard firmware 
This is the Disassembly of the 2nd generation dashboard firmware from a NIU N1s electric scooter (Model 2018+)

# Hardware
Besides the LCD, a buck-converter and RS485 receiver the dashboard contains an STM32F0308T6 32-bit micro controller from STmicro.

That's an ARM Cortex®-M0 core and run at speeds up to 48 MHz having 64k of flash and 8k of RAM.
Aditionally there are two USARTs, two SPI and two I2C controllers built in. 

To learn more about it visit https://www.myniu.org/2nd-gen-dashboard/

# Code
This is the "first shot" at the disassembly mainly adding the knwon addresses of the USARTs etc. hinting towards the functionality of those functions using them.
