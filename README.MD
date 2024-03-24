# The RepRap Expansion Module System
A simple, open-source expansion system allowing easy addition of SPI, I2C, and GPIO devices to a controllerboard.

See [STANDARD.MD](Standard/STANDARD.MD) for details on module and slot design.
The KiCad footprint and symbol can be found in the [`/Footprint-Symbol`](/Footprint-Symbol) directory.

# Modules:

| Creator | Name           | Comment / Description                                          | Path                                      | Last Changed    |
|---------|----------------|----------------------------------------------------------------|-------------------------------------------|-----------------|
| Pera    | TLA2518 Module | Single-Sided SMD; Uses a TLA2518 to add 8 ADC inputs, over SPI. Untested. | [`Modules/TLA2518-8xThermistor`](Modules/TLA2518-8xThermistor) | March 22nd, 2024|

# License
Unless otherwise indicated, the contents of the [`/Modules`](/Modules) directory are licensed under CERN-OHL-v2+, see [LICENSE.txt](LICENSE.txt) for more details.

The contents of the [`/Standard`](/Standard) directory are licensed under CC0, see [CC0.txt](CC0.txt) for more details.