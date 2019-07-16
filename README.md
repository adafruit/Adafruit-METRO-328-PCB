## Adafruit METRO 328 PCB

<a href="http://www.adafruit.com/products/2466"><img src="assets/image.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit METRO 328. Format is EagleCAD schematic and board layout

For more details, check out the product page at
* https://www.adafruit.com/products/2466

### Description

We sure love the ATmega328 here at Adafruit, and we use them a lot for our own projects. The processor has plenty of GPIO, Analog inputs, hardware UART SPI and I2C, timers and PWM galore - just enough for most simple projects. When we need to go small, we use a Metro Mini, but when size isn't as much of a concern, and a USB-serial converter is required, we reach for an Adafruit METRO.

METRO is the culmination of years of playing with AVRs: we wanted to make a development board that is easy to use and is hacker friendly.

ATmega328 brains - This popular chip has 32KB of flash (1/2 K is reserved for the bootloader), 2KB of RAM, clocked at 16MHz
Power the METRO with 7-9V polarity protected DC or the micro USB connector to any 5V USB source. The 2.1mm DC jack has an on/off switch next to it so you can turn off your setup easily. The METRO will automagically switch between USB and DC.
METRO has 20 GPIO pins, 6 of which are Analog in as well, and 2 of which are reserved for the USB-serial converter. There's also 6 PWMs available on 3 timers (1 x 16-bit, 2 x 8-bit). There's a hardware SPI port, hardware I2C port and hardware UART to USB.
GPIO Logic level is 5V but by cutting and soldering closed a jumper, you can easily convert it to 3.3V logic
USB to Serial converter, there's a hardware USB to Serial converter that can be used by any computer to listen/send data to the METRO, and can also be used to launch and update code via the bootloader
Four indicator LEDs, on the front edge of the PCB, for easy debugging. One green power LED, two RX/TX LEDs for the UART, and a red LED connected to pin PB5
Easy reprogramming, comes pre-loaded with the Optiboot bootloader, which is supported by avrdude and only uses 512 bytes.
Beautiful styling by PaintYourDragon and Bruce Yan, in Adafruit Black with gold plated pads.
Works with all Adafruit designed shields!
This version of the METRO 328 comes as a fully assembled and tested development board but without any headers or the DC jack attached. We do include these parts so that you can solder on if you like, or you can solder wires or header directly to the breakout pads. We also include 4 rubber bumpers to keep it from slipping off your desk.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike. See license.txt for additional details.

Derivative of "Arduino UNO R3 Reference design" (http://www.arduino.cc/en/Main/ArduinoBoardUno)

All text above must be included in any redistribution
