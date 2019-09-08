## Glossary Of Terms

### Raspberry PI
The Raspberry Pi is a low cost, credit-card sized computer that plugs into a computer monitor or TV, and uses a standard keyboard and mouse. It is a capable little device that enables people of all ages to explore computing, and to learn how to program in languages like Scratch and Python. It’s capable of doing everything you’d expect a desktop computer to do, from browsing the internet and playing high-definition video, to making spreadsheets, word-processing, and playing games.
What’s more, the Raspberry Pi  has the ability to interact with the outside world, and has been used in a wide array of digital maker projects, from music machines and parent detectors to weather stations and tweeting birdhouses with infra-red cameras.

### Polarity - Electrical polarity
(positive and negative) is the term used to describe the direction of current flow in an electrical circuit.

### Resistor
A resistor is a passive two-terminal electrical component that implements electrical resistance as a circuit element. In electronic circuits, resistors are used to reduce current flow, adjust signal levels, to divide voltages, bias active elements, and terminate transmission lines, among other uses.

### L.E.D
A light-emitting diode (LED) is a semiconductor light source that emits light when current flows through it.

### Breadboard
A breadboard is a solder-less device for temporary prototype with electronics and test circuit designs. Most electronic components in electronic circuits can be interconnected by inserting their leads or terminals into the holes and then making connections through wires where appropriate.

### Voltage
An electric circuit is formed when a conductive path is created to allow electric charge to continuously move. This continuous movement of electric charge through the conductors of a circuit is called a current, and it is often referred to in terms of “flow,” just like the flow of a liquid through a hollow pipe. The force motivating charge carriers to “flow” in a circuit is called voltage.

### GPIO
The GPIO (General Purpose Input Output) pins are integrated into the circuit board of the computer. Their behavior can be controlled by the user to allow them to read data from sensors, and control components like LEDs, motors, and displays. Older models of the Pi had 26 GPIO pins, while the newer models all have 40. 

### Active Buzzer
An active buzzer has a built-in oscillating source, so it will make sounds when electrified. But a passive buzzer does not have such source, so it will not beep if DC signals are used; instead, you need to use square waves whose frequency is between 2K and 5K to drive it.

### HC-SR04 Ultrasonic Sensor
A sensor that uses sound waves to measure distance. There are four pins in the module Vcc, Gnd, Trigger and Echo. This module operates at 5 volts with a consumption of 15 mA current.  It can measure the distance effectively starting from 2 cm to 500 cm (5 Meters).  The module works as follows if you send a supply a short 10uS pulse to the trigger input to start the ranging, then the module will send out an 8 cycle burst of ultrasound at 40 kHz. This 8 burst pattern hits the object and reflects back. Now once the 8 burst pattern is sent, the Echo pin is set  high (i.e 5 V ) and when the signal reflects and comeback the Echo pin is set  low (0 V). This time duration for which the Echo pin stays high is the time taken for ultrasonic wave to travel and comeback, yes the round trip.
