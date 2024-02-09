This code was written for STM L432KCU6 microprocessor.

It sends a CAN message of 0x32 0xAA every 0.5 seconds.
See the photo for the circuit diagram:
![alt text](https://github.com/suspicious-salmon/CanWriter/blob/main/assets/circuit_diagram.jpg?raw=true)

The resistor between pins 2 and 8 is 10k and connects to ground.
The resistor between pins 6 and 7 is 120k and is the CAN termination resistor.
