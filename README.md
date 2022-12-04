# AccDec_8Servos_8Relais

Dcc Accessory Decoder to drive 8 servo plus 8 relais for frog polarization

Originally derived from an example of library NmraDcc.

Library required:

- [NmraDcc] (public)
- [ConfCVlib] (manual installation)
- [DccSerialCom] (manual installation)

Features:

- 8 Servo outputs.
- 8 mocro 12V relais for frog polarization with N, NO and NC contacts.
- customizable start/stop points, travelling speed, default position ad power on, save last position, switch point for servo.
- Separate power socket or autopower via DCC.
- Sigle address mode (continuos address for each output) or multiple address mode (each output has it own address).

Designed to be configured with the custom PC tool [DecoderConfigurator], or in standardize way via CV.

[NmraDcc]: https://github.com/mrrwa/NmraDcc
[ConfCVlib]: https://github.com/M5Ross/ConfCVlib
[DccSerialCom]: https://github.com/M5Ross/DccSerialCom
[DecoderConfigurator]: https://github.com/M5Ross/DecoderConfigurator
