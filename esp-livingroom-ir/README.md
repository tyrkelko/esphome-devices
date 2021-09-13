IR Blaster with IR Reciever and Temperature sensor, ideal for A/C control.
Includes a PIR motion sensor for motion based rules.
This is an ESPHOME DIY A/C controller I've built for working with home assistant.

It easily mimics a midea r6/bge remote control for my electra and tornado A/C.

Parts I used in this project:
1 * NODEMCU V3 development board

1 * BF494 NPN transistor for switching the IR LEDs

1 * 10 kOhm resistor for current limit on the BF494 transistor base

3 * 36 Ohm resistor for current limit on the IR LED

3 * 5mm IR LED

1 * TSOP IR sensor scraped from an old dvd player

1 * DHT11 temperature sensor

1 * SR-HC501 PIR motion sensor

1 7*5 cm Performance board

Female and Male connectors for attaching the NODEMCU V3 to the shield and for breaking out the wires for the PIR sensor

Some wires

Software used:
homeassistant server
esphome

<img width="246" alt="esp-livingroom-ir-lovelace-ui" src="https://user-images.githubusercontent.com/6322663/133160703-68ff88fe-bc8c-4690-b329-9acf1fb97563.png">

The component for homeassistant eventually looks like the above.
