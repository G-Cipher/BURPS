BURPS
=====

BeagleBone Universal Removed Pololu Steppers

BeagleBone Black cape providing a semi-generic optoisolated breakout for 4
stepper axis outputs and 3 limit switch inputs. The BBB I/O pin configuration
is chosen for compatibility with [BeagleG] for testing purposes.
Output is a male DB-25 connector, with pinout selected for compatibility with
[FlashCut CNC] stepper driver electronics.

BURPS is therefore a stripped-down implementation of [BUMPS], the
BeagleBone Universal Multi Pololu Steppers board.

The BURPS PCB design files were created with [Cadsoft Eagle] 5.12.0. This
board is designed for a prototype milling process, and may not be suitable
for commercial fabrication.

PCB v1.0 uses a male DB-25 connector mounted on the bottom of the board for
external signals. This was found to conflict with peripherals plugged into
the USB type A or micro HDMI ports.

PCB v1.1 replaces the DB-25 connector with a dual-row 26-pin header. The
pinout of the header corresponds to a male DB-25. A ribbon cable assembly
with header IDC and male DB-25 IDC will connect the signals correctly.

The graphics below depict PCB v1.0.

![pcb]
![schematic]

[beagleg]: https://github.com/hzeller/beagleg
[flashcut cnc]: http://www.flashcutcnc.com/cnc-controls/stepper-controls-motors
[bumps]: https://github.com/hzeller/bumps
[cadsoft eagle]: http://www.cadsoftusa.com/
[pcb]: https://raw.githubusercontent.com/G-Cipher/BURPS/master/BURPS-v1.0-PCB-850x460.png
[schematic]: https://raw.githubusercontent.com/G-Cipher/BURPS/master/BURPS-v1.0-schematic-2048x1378.png
