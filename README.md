# 8In8Out

* The module adds 8 microcontroller inputs and 8 outputs via the I2C bus.
* The inputs are optically isolated.
* The module features an interrupt line, eliminating the need for continuous polling of the inputs to check for changes.
* The module automatically signals a state change on any of the inputs via the interrupt line.
* The modules are available for three input voltage levels: 5 V, 12 V, and 24 V.
* The outputs are of the open-collector type and include a protection diode.
* Relay coils can be connected directly to them.
* When connecting inductive loads—such as relay coils—to the module's outputs, pins 1 and 2 of connector J2 must be connected.
* The module is based on the Texas Instruments TCA6416 integrated circuit.
* Communication takes place via the I2C bus.
* The module features I2C bus isolation based on Texas Instruments ISO1540 devices.
* The I2C bus address can be configured using solder jumpers.
