Matrix
======

Matrix Orbital Emulated Arduino HD44780 Device for Arduino Nano V3.0

Breadboard
Edit: Do not use a capacitor for Contrast just connect it to the pin directly for lcd 20x02 and use a diode (1n4148) for lcd 16x02
I recommend using a small NPN transistor to drive the backlight, emitter to ground, collector to backlight anode and base connected with a small resistor the uC BackLight PIN(i use BC337 and 12k resistor).
![Breadboard](http://s10.postimg.org/roe0sj1ll/tisplay_breadboard.png)

Circuit Diagram

![Circuit Diagram](http://s23.postimg.org/ijjwnjtqz/tisplay_circuit.png)
