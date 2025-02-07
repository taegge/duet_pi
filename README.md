# Purpose

This is a Rasperry Pi CM4/CM5 carrier board for elegantly interfacing an SBC to the Duet3d Duet 3 6HC (https://www.duet3d.com/duet3mainboard6hc). Intended to be mounted back-to-back, the footprint and mounting holes are identical. In that configuration, the 26 pin IO connectors are also directly inline, supporting either a short wire or direct board-to-board connection.

## Features
 * Same input voltage range as Duet 3 6HC: 12V-48V (Vin)
 * Onboard 5V @ 5A regulatoin for raspberry pi and accessories.
 * Onboard selectable 12V / 24V @ 5A regulator  (Vreg)
 * Four high current, independantly fused power distribution ports. Selectable between Vreg or Vin
 * High Speed IO: ethernet, USB A, USB C, HDMI, DSI/CSI, microSD, m.2
 * JST and Molex (5v) fan connections.

# Board Layout

![image](images/pcb_front.jpg)
![image](images/pcb_back.jpg)

# PCB Fabrication

For impedance control, pcb was designed for the specific board stackup from jlcpcb: JLC041611-3313

4 layers. 1oz copper inner and outer. 1.6mm thick

![image](images/stackup.png)
provided by https://jlcpcb.com/pcb-impedance-calculator

