# 40A Smart Switch Analog Subsystem
The analog subsystem of a 40A smart analog switch. Contains a DAC, an ADC with a 2-channel mux and ADC driver, an isolated DC-DC, isolated FET driver, isolated voltage amp, current sense amp, a current sense amp with digitally adjustable range (by DAC).

This design is meant to power a smart MCU-controlled multi-channel power path controller. Designed to route power from a 12V system, to a battery charger, to power a computer system, and a radio, as a N:M:O switch matrix, if desired, offering absolute flexibility and scalability due to the isolated architecture.

This is a demo board, optimized for prototyping.

![pcb_top](https://github.com/user-attachments/assets/ae502a78-fedb-4412-9dcf-aa7905acede8)

This board is used to drive an array of N-channel MOSFETs as a switch. The current sense amp and the ADC and used for sampling and digitizing the current. The isolated amp can be use to measure voltage. The board is fully isolated, and can be used in a multichannel switch configuration for any smart power path control.

## N-FET Switch Analog board

Test board capable of handling siwtching of 40A (13.8V) without cooling. Can handle 70A with passive cooling. Uses 6 x Infineon IQDH35N03LM5CG FETs, in back to back source to source configuration.

![fet_switch17](https://github.com/user-attachments/assets/62145458-0b04-47f9-b261-2152dd26789c)
![fet_switch17_bottom](https://github.com/user-attachments/assets/101e5601-3095-4ea2-8c77-63f8e06ae2bb)
