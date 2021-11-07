# studiotoys
Code for a 10 button transport controller for studio one
This arduino sketch is designed to work with an Arduino Leonardo in Studio One.
It requires setting up 2 controllers, a generic controller and a Mackie control under options external devices.
the generic controller should be set send to - none, receive from - arduino
the mackie controller should be set  send to - arduino, recieve from - none
the sketch sets up 10 buttons on digital pins 0-9
and 3 leds, pin 10 tied to play, pin 11 tied to record, pin 12 always on as back lighting
this sketch requires the control surface library https://tttapa.github.io/Control-Surface-doc/Doxygen/index.html#documentation
