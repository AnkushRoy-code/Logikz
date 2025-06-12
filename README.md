
# Logikz

I designed a simple circuit board that can function as three different logic
gates:- `AND`, `OR`, and `NOR`

### Making of Logikz
This is my third PCB and this time around I wanted to know how transistors
work, and also wanted to know how logic gates work. I myself implemented the
`AND` and `OR` gates but had to look up how to do a `NOR` gate. Later I also
changed how my `OR` gate works looking at the implementation of `NOR` gate.

The first iteration would've never worked, because of absolutely no current
calculations done. Used [circuit.js](https://www.falstad.com/circuit/circuitjs.html) to fix my implementation.
Earlier it had like 5 buttons, two for `A` and `B` inputs and the rset for
choosing between the gates. But had to ditch that idea because current it
didn't work in the simulation. Now I have 9 buttons, `A` and `B` for each
gates, so total 3 `A` and 3 `B` input buttons.

Reason why the first iteration didn't work: It had something to do with
"current takes the least resistive path", it is hard to explain in text.

The simulation file is present in `~/logikz_circuitjs.txt`, download it and
load it in [circuit.js](https://www.falstad.com/circuit/circuitjs.html) to see my project in action.

### PCB

### SChematic

### BOM
`~/BOM.csv` has BOM of this project.

| QTY            | Name              |
| -------------- | ---------------   |
| 1              | Battery Holder    |
| 1              | LED               |
| 6              | NPN Transistor    |
| 2              | 220 Ohm Resistor  |
| 5              | 4.7k Ohm Resistor |
| 9              | Push Button       |


Made by `@Ankush Roy` in Slack from Hack Club

Made as a part of https://solder.hackclub.com/!
