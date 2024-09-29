# 40A Smart Switch Analog Subsystem
The analog subsystem of a 40A smart analog switch. Contains a DAC, an ADC with a 2-channel mux and ADC driver, an isolated DC-DC, isolated FET driver, isolated voltage amp, current sense amp, a current sense amp with digitally adjustable range (by DAC).

This design is meant to power a smart MCU-controlled multi-channel power path controller. Designed to route power from a 12V system, to a battery charger, to power a computer system, and a radio, as a N:M:O switch matrix, if desired, offering absolute flexibility and scalability due to the isolated architecture.

This is a demo board, optimized for prototyping.

![pcb_top](https://github.com/user-attachments/assets/ae502a78-fedb-4412-9dcf-aa7905acede8)

This board is used to drive an array of N-channel MOSFETs as a switch. The current sense amp and the ADC and used for sampling and digitizing the current. The isolated amp can be use to measure voltage. The board is fully isolated, and can be used in a multichannel switch configuration for any smart power path control.
