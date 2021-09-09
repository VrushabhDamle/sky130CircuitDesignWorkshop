# sky130CircuitDesignWorkshop
# **Day 1: Basics of NMOS Drain Current (Id) vs Drain-to-source Voltage (Vds)**

On the first day the of the workshop, a basic introduction to MOSFETs and SPICE simulations was given. Basic terminologies of MOSFETs and the regions of operation were introduced. A few drain current (Id) equations were derived and the first SPICE simulation was successfully performed. The syntax for the simulation files was also explained and the method to create modules was also taught.

## **Part 1: Introduction to Circuit Design and SPICE simulations**

What was learnt:

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

What was learnt:

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

What was learnt:

•	SPICE model parameters

•	SPICE simulation flow diagram

![spice workflow](https://user-images.githubusercontent.com/89193562/132533155-7affa537-beb3-4aa4-8eab-b4ff3aaab64d.JPG)

•	SPICE netlist for our NMOS

•	Definition of nodes and the method to identify them

•	SPICE syntax

•	Method to save SPICE model

•	Method to write code for SPICE simulation

Lab Activity:

![day1 ngspice command](https://user-images.githubusercontent.com/89193562/132533223-85fac5e7-3073-43fc-9d14-a248e9116a2e.JPG)

Figure 1. The snap shot of the terminal window for Day1 activity

![1631113926996](https://user-images.githubusercontent.com/89193562/132536273-27086fab-f96a-444b-b4f3-88e3ded13be4.jpg)

Figure 2. The snap shot of the NMOS that is used for the activity

![1631113614117](https://user-images.githubusercontent.com/89193562/132535503-e272eee6-35b4-4763-832c-367f36209678.jpg)

Figure 3. The snap shot of SPICE netlist of the above NMOS

![day1 spice model](https://user-images.githubusercontent.com/89193562/132533338-e2298388-5d87-49a2-b5e2-6156ce69c46d.JPG)

Figure 4. The snap shot of the output window of the Day1 activity
