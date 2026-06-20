# LM7805-5V-Power-Supply

# Circuit Operation
The DC input passes through a 1N4007 diode providing reverse polarity protection against accidental incorrect connection. A 470µF electrolytic capacitor filters residual low-frequency ripple from the DC source. A 0.33µF ceramic decoupling capacitor on the LM7805 input pin suppresses high-frequency noise as recommended by the device datasheet. The LM7805 (TO-220) voltage regulator outputs a precise, regulated 5V DC from inputs spanning 7V to 35V. A 0.1µF ceramic decoupling capacitor on the output pin ensures voltage stability and prevents regulator self-oscillation. A 300Ω current-limiting resistor safely drives a red LED to provide a visual power-live verification.

## SPICE Simulation Results
* Input Voltage: 9V DC,
* Output Voltage: 4.999573V (Essentially perfect 5V regulation),
* Output Ripple: Zero (completely flat transient response),
* Simulation Engine & Command: KiCad 8 (ngspice) | '.tran 10u 100m.',
* Conclusion: Design electrically verified and validated before finalizing the physical PCB layout.

## Technical Deliverables
* Full KiCad 8 schematic with zero ERC errors,
* Integrated ngspice simulation schematic and transient analysis results,
* 2-layer PCB layout featuring a low-impedance ground plane and optimized power trace widths,
* DRC verified with zero errors (production-ready Gerber files exported),
* Verified 3D hardware assembly view

<img width="1470" height="956" alt="Image" src="https://github.com/user-attachments/assets/4b2291ce-5e62-4661-bacd-7dd55eed535c" />

<img width="1470" height="956" alt="Image" src="https://github.com/user-attachments/assets/9d7df04f-143f-4e55-8f69-8aa90f940a57" />

<img width="1470" height="956" alt="Image" src="https://github.com/user-attachments/assets/a2a132ae-12be-412f-8ba9-1d0e0a412cb7" />

<img width="1470" height="956" alt="Image" src="https://github.com/user-attachments/assets/6bd46717-6bb3-46ec-9323-080c25187354" />

<img width="1470" height="956" alt="Image" src="https://github.com/user-attachments/assets/bf49a099-bc77-44b7-a989-3c6e824cab38" />

<img width="1470" height="956" alt="Image" src="https://github.com/user-attachments/assets/8b1fad2e-a1dc-49aa-95e2-f27691f1acde" />
