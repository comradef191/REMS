# Slot Requirements

All REMS slots must feature the SCK, SDO and SDI pins necessary for SPI, the SDA and SCL pins for I2C, and three pins wired directly to the GPIO of the MCU.

All REMS slots must be wired up with 12V, 5V, 3V3 and Ground. The three VM pins should be wired up to the boards 24+ power input, or have its own dedicated power input. This is to allow for modules requiring higher voltages than 12v, such as stepper drivers and mosfets.

REMS slots should be positioned on the controllerboard such that the striped section above pins 9 & 1 overhangs the board edge.
The striped section below pins 16 & 8 should be left clear of connectors and other large components which may obstruct REMS modules.
(See below images)

It is recommended to keep the area inside the confines of a slot clear to allow for the markings to be easily read.

Where no dedicated header is provided, 'Special GPIO' such as UART, PWM, and ADCs should be routed to a modules GPIO pins and clearly marked.
In the case of UART, RX should be IO1, and TX should be IO2.

# Module Requirements
Modules must not be any larger than 21.59mm wide and 34.5948mm long. This is to prevent space conflicts with neighbouring modules.

Modules may omit pins 11-14 if such voltages are unnecessery. Pins 9-10 & 15-16 should remain present regardless of needs for rigidity and secureness.

Modules making use of the VM pins must be able to safely run on 24v. Modules using these pins must clearly indicate the maximum voltage the module can be expected to operate at.

Modules must indicate to a user, clearly, which pin is IO1; On the included footprint, `REMS Stick`, this is done with a solid box around Pin 1

# Images
![Image](/Standard/Footprint-2D.png)

![Image](/Standard/Footprint-3D.png)