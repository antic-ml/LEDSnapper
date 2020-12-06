# LEDSnapper
LED Snapper is a simple, compact diagnostic board for Arduino breadboard projects. It
is suitable for Arduino makers, because it is a 5 volt
module. It is cheap to make too: you can make 10 of them for around a $1.50 per board.

If you are forever plugging LEDs and resistors into breadboards to monitor
signal output from your Arduino, then you may find this board useful. It plugs
into your breadboard and there are 8 pins connected to 5 mm LEDs 
which you can use to monitor signals. I call it **LEDSnapper**, because it 
snaps into your breadboard.

![Breadboard](images/breadboard-shot.JPG)

Photo of the board being used to test Arduino pin output.

![Front of board](images/front-lsb.JPG)

Top of the board.

![Back of board](images/back-lsb.JPG)

Back of the board. 5V8 means it is a 5 volt module with 8 pins.


The module is also suitable for 5 volt circuits other than the Arduino.

Component List
---------------
- 8 x 5 mm LED in the color of your choice
- 8 x 220 Ohm resistors
- Male pin headers

The board is marked up with the components, so you should have little difficulty
soldering it.

How To Use
----------

Connect up the GND pin and then connect one, or more of the 8 pins
connected to LEDs to +5 Volts, or the Arduino pins. Don't supply more
than 5 volts to the pins, or you may burn out the LEDs.

Choose from 3 different boards
------------------------------

There are 3 different versions of the board. Check the PCB layout images
below to see which one you require. Below each image you will find the
name of the associated Gerber files for that board.

![5V8-LSB-PCB](images/5V8-LSB-PCB.png)

Board #1: Pin numbers run left to right.
**Gerber Files:** 5V8-LSB-PCB.zip

![5V8-LSB-PCB-1.1](images/5V8-LSB-PCB-1.1.png)

Board #2: Pin numbers run left to right but this board occupies slightly less real estate on your breadboard.
**Gerber Files:** 5V8-LSB-PCB-1.1.zip

![5V8-MSB-PCB](images/5V8-MSB-PCB.png)

Board #3: Pin numbers run in reverse order from left to right. Useful for reading binary numbers.
**Gerber Files:** 5V8-MSB-PCB.zip

Getting the PCB manufactured
----------------------------

A number of companies exist that will allow you to upload Gerber files
to their website and they will manufacture the boards for you. Some, like
[JLCPCB](https://jlcpcb.com/) and [PCBWAY](https://pcbway.com/) will make the boards at a very low cost
and give you ten of them. Expect to pay around $2 for ten boards + shipping. These
companies are about the cheapest I have found, but feel free to
shop around.

So simple, I could make one myself!
-----------------------------------

If you are an experienced electronics hobbyist, or engineer then yes, of course
you could easily. This project is primarily designed for beginners and makers to give them
confidence in ordering components and a PCB for manufacturing. Plus, they get
to build a simple, but useful piece of test equipment that they can use for
their breadboard projects. My hope is that people will build LEDSnapper and
then have the confidence to move on to more complex open source hardware and
build that too. Maybe this project will provide someone with the impetus to
kickstart an open source hardware project of their own.




