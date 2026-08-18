# AG328X-REV-1
AG328X REV-1 is a compact, redesigned implementation of the Arduino UNO platform, developed with
the objective of improving the original UNO architecture in terms of form factor, power architecture, USB
connectivity, protection, serviceability, and PCB integration.
The design retains the core functionality based on the ATmega328P, while keeping a dedicated
ATmega16U2 USB-to-serial interface and a redesigned power-management architecture. Rather than
directly reproducing the conventional reference design, AG328X restructures several functional sections to
achieve a more compact and integrated hardware platform.
The complete PCB is designed with an overall dimension of 34 mm × 34 mm, a 1.6 mm finished board
thickness, and a 4-layer PCB stack-up, which is 68.44% smaller in size compared to the original UNO board.
The four-layer implementation provides additional routing resources and dedicated copper areas for power
and ground distribution, enabling the compact board dimensions without compromising the electrical
organization of the design. For further info, go through @Documentation Section.
