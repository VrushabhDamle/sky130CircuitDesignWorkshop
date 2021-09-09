# sky130CircuitDesignWorkshop
# **Day 1: Basics of NMOS Drain Current (Id) vs Drain-to-source Voltage (Vds)**

On the first day the of the workshop, a basic introduction to MOSFETs and SPICE simulations was given. Basic terminologies of MOSFETs and the regions of operation were introduced. A few drain current (Id) equations were derived and the first SPICE simulation was successfully performed. The syntax for the simulation files was also explained and the method to create modules was also taught.

## **Part 1: Introduction to Circuit Design and SPICE simulations**

**_What was learnt:_**

•	The importance of W/L ratio

•	Need of SPICE

•	NMOS design and specifications

•	Threshold Voltage (Vt)

•	Concept of Strong Inversion

•	Impact of Source-to-bulk Voltage (Vsb)

•	Threshold Voltage Equation

![Threshold voltage equation](https://user-images.githubusercontent.com/89193562/132532135-3de1b633-d02f-48b0-b9c6-030c40f2c30a.JPG)

•	Body Effect Coefficient expression

![body effect coeffecient equation](https://user-images.githubusercontent.com/89193562/132532303-8b6fda87-3bc7-48ba-a99b-c7ffe5c4a969.JPG)

•	Fermi Potential Equation

![fermi potential equation](https://user-images.githubusercontent.com/89193562/132532339-de5b4411-323e-48b2-bb3d-68b20e54dcef.JPG)


## **Part 2: NMOS Resistive region and Saturation region of operation**

**_What was learnt:_**

•	Theory about Resistive region

•	Formula for charge induced at any point ‘x’

![induced charge at x](https://user-images.githubusercontent.com/89193562/132532646-03b38d68-de8d-45b1-92cf-7c240f922d2e.JPG)

•	First order analysis

•	Gate oxide capacitance formula

![gate oxide capacitance formula](https://user-images.githubusercontent.com/89193562/132532783-30c5d29d-4405-4833-a4b8-942d4787f50d.JPG)

•	The two kinds of current: Drift current and Diffusion current

•	Drift current (Id) formula

![drift current formula](https://user-images.githubusercontent.com/89193562/132532906-9238aba4-134e-4b1f-a00b-f7e126479071.JPG)

•	Condition on Vds for the MOSFET to be in linear/resistive region or saturation/pinch-off region

•	Dependance of Id on Vds in pinch-off region


## **Part 3: Introduction to SPICE**

**_What was learnt:_**

•	SPICE model parameters

•	SPICE simulation flow diagram

![spice workflow](https://user-images.githubusercontent.com/89193562/132533155-7affa537-beb3-4aa4-8eab-b4ff3aaab64d.JPG)

•	SPICE netlist for our NMOS

•	Definition of nodes and the method to identify them

•	SPICE syntax

•	Method to save SPICE model

•	Method to write code for SPICE simulation

**_Lab Activity:_**

![day1 ngspice command](https://user-images.githubusercontent.com/89193562/132533223-85fac5e7-3073-43fc-9d14-a248e9116a2e.JPG)

Figure 1. The snap shot of the terminal window for Day1 activity

![1631113926996](https://user-images.githubusercontent.com/89193562/132536273-27086fab-f96a-444b-b4f3-88e3ded13be4.jpg)

Figure 2. The snap shot of the NMOS that is used for the activity

![1631113614117](https://user-images.githubusercontent.com/89193562/132535503-e272eee6-35b4-4763-832c-367f36209678.jpg)

Figure 3. The snap shot of SPICE netlist of the above NMOS

![day1 spice model](https://user-images.githubusercontent.com/89193562/132533338-e2298388-5d87-49a2-b5e2-6156ce69c46d.JPG)

Figure 4. The snap shot of the output window of the Day1 activity


# **Day 2: Velocity Saturation and basics of CMOS inverter VTC**

## **Part 1: SPICE simulation for lower nodes and velocity saturation effect**

**_What was learnt:_**

•	The distribution of various regions of operation of NMOS over the graph plotted between Ids and Vds.

![plot (0)](https://user-images.githubusercontent.com/89193562/132674785-f6e3444f-2e00-45d9-ac47-7f4c8e040074.png)

Figure 5. The snap shot of various regions of operation of NMOS on graph plotted between Ids and Vds.


•	The theory about cut-off region of NMOS.

•	Short channel effect

•	Velocity Saturation effect

![velocity saturation equation](https://user-images.githubusercontent.com/89193562/132674315-002da47e-65d4-4976-b2c0-b309dee76df7.JPG)

•	The modes of operation for long channel (>250nm) devices and short channel (<250nm) devices.

•	The equation of Id for long channel and short channel devices

![Id equation](https://user-images.githubusercontent.com/89193562/132674348-c1e9e289-f766-4750-94f1-eb4cfe5189eb.JPG)

•	The various modes when the value of Vmin is different

•	Velocity Saturation causes device to saturate early

**_Lab Activity:_**

![ngspice command window with vgs sweep](https://user-images.githubusercontent.com/89193562/132675164-206b1eeb-8cba-44a8-af4f-bf4322e37550.JPG)

Figure 6. The snap shot of terminal window for plot between Ids and Vds for short channel device

![plot window with vgs sweep](https://user-images.githubusercontent.com/89193562/132675399-e8f69dc7-f222-4e91-81fc-4cb2639213d4.JPG)

Figure 7. The snap shot of output window for plot between Ids and Vds for short channel device

![ngspice Id vs Vgs curve command window](https://user-images.githubusercontent.com/89193562/132675473-18cd0d22-a956-4c4a-978b-e4837c292d70.JPG)

Figure 8. The snap shot of terminal window for plot between Ids and Vds for short channel device without the sweep for vdd

![plot window Id vs Vgs](https://user-images.githubusercontent.com/89193562/132675655-f779b9be-bcee-4d31-8a62-6204bc0bca40.JPG)

Figure 9. The snap shot of output window for plot between Ids and Vds for short channel device without the sweep for vdd

## **Part 2: CMOS voltage transfer characteristics (VTC)**

**_What was learnt:_**

•	Transistor as a switch

•	The working of CMOS

•	What happens when Vin is ‘high’ and equal to ‘vdd’ and what happens when Vin is ‘low’ and equal to ‘0V’

•	The flow of current when Vin is ‘high’ and when Vin is ‘low’

•	Defined terminologies in CMOS inverter

•	By observation:

    - For the NMOS voltage equations
  
    ![NMOS relations](https://user-images.githubusercontent.com/89193562/132678214-102b9070-69f0-4e5b-bf3d-8857a16eb2d3.JPG)
    
    - For the PMOS voltage equations
    
    ![PMOS relations](https://user-images.githubusercontent.com/89193562/132678417-5a8f967b-1829-47a4-a5a4-2c941d53742b.JPG)

    - For the relationship between the currents

    ![current relations](https://user-images.githubusercontent.com/89193562/132678310-f82ca578-2b01-45df-9336-560547917b96.JPG)
