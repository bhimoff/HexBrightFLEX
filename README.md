Brandon Himoff's HexBright Mod
=======================

hexbright_bjh
-----------------
This firmware has: 
* a lower low
* makes it so that after five seconds you go from low or medium directly to off 
* uses dazzle instead of blink
* cherry picked the improved dazzle from https://github.com/digitalmisery/HexBrightFLEX
* cherry picked the SOS mode from hhttps://github.com/jaebird/samples.git
* required a 2 second press from dazzle to get to SOS
* uses the accelerometer to power down after 10 minutes motioneless to save battery

More to come.


These below are from the original:

hexbright_factory
-----------------
This is the software that ships with the Hexbright Flex.  Button presses cycle
through off, low, medium, and high modes.  Hold down the button while off for 
blinky mode.

hexbright4
---------------------
Fancier than the factory program, but designed for everyday usability.  Button
presses cycle through off, low and high modes.  Hold the light horizontally,
hold the button down, and rotate about the long axis clockwise to increase
brightness, and counter-clockwise to decrease brightness- the brightness sticks
when you let go of the button.  While holding the button down, give the light a
firm tap to change to blinky mode, and another to change to dazzle mode.

hexbright_demo_morse
--------------------
Flashes out a message in morse code every time you press the button.  Nothing 
else.  The message and speed are easy to change- you can see and change both 
in the first lines of code.

hexbright_demo_taps
-------------------
Hold the button down, and with your other hand firmly tap on the light.  Tap
some more times, and let go of the button.  The exact sequence of taps will
be recorded and then played back as flashes until you press the button again
to turn off.

hexbright_demo_momentary
------------------------  
Light turns on only while the button is being held down.  That's it.

hexbright_demo_dazzle
---------------------
Light runs in dazzle mode only as long as the button is being held down.

hexbright_demo_fades
--------------------  
Hold the button down, and light fades up and down.  Let go, and it holds the 
current brightness.  Another press to turn off.
