# CANdb++

This repo is used to track and document the CAN network for ePBR.

* [Install CANdb++ for free](https://www.vector.com/int/en/products/products-a-z/software/candb/#c104632)
* [CANdb++ user manual](https://usermanual.wiki/m/89328a2483ec8788fc022c1d6f3bf5b89802a5c911ed5d98ac0586a9cc987b0a_pdf)

Definitions:
* `Network`: an array of controllers connected by a CAN bus.
* `ECU`: Electronic Control Unit; any unit that interacts with a CAN network.
* `Network Node`: An ECU that performs its tasks in a CAN network.
* `Message`: A frame of data as defined by a CAN protocol. Either standard, extended, or J1939. May contain many signals.
* `Signal`: An independant piece of data