# MCP7382T-2DCI Breakout Board
![image](https://user-images.githubusercontent.com/107767719/210141274-d4c72c1f-71ed-4e9a-b540-cebfbb1cedc9.png)
The schematic above is a simple breakout board designed to evaluate the MCP73832 IC. This IC is capable of charging a single Li-Ion cell to its fully voltage of 4.2 Volts and will stop supplying current to the battery once it has been fully charged.


Components:

C1,C2-Filtering Capacitors

D1-ESD Protection

D2-Status LED indicator

J1-Micro USB type B input for power

J2,J3,J4,J5,J6-Access to each pin of the MCP73832

Rled-Current limiting resistor for the status LED

Rprog-Program resistor which determines the charge current. See figure 2-4 in datasheet to determine charge current.

U1-MCP73832-2DCI, single cell Li-Ion charger IC.

Pin Description:

1-STAT-OUTPUT. Low indicates charging, HIGH Z indicates charge cycle complete, no battery present, or shutdown.

2-VSS-GND. Pin header connects to negative termnial of Li-Ion cell.

3-VBAT-POWER OUTPUT. Pin header connects to positive termnial of Li-Ion cell.

4-VDD-POWER INPUT. Use Vbus from Micro USB to power MCP7382T

5-PROG-DIGITAL INPUT. Current regulation input pin. Left floating or applying a logic-high input signal disables device and terminates charge cycle.

![image](https://user-images.githubusercontent.com/107767719/210141210-5514fc17-79f9-49f0-9d3d-8e01fed53402.png)

Above image is the 3D viewer of the front side of the board in Kicad. 

![image](https://user-images.githubusercontent.com/107767719/210141231-9a1161dc-7a85-49da-977d-80a875ae498a.png)

Above image is the 3D viewer of the back side of the board in Kicad. 
