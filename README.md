# sky130CircuitDesignWorkshop
# **Day 1: Basics of NMOS Drain Current (Id) vs Drain-to-source Voltage (Vds)**

On the first day the of the workshop, a basic introduction to MOSFETs and SPICE simulations was given. Basic terminologies of MOSFETs and the regions of operation were introduced. A few drain current (Id) equations were derived and the first SPICE simulation was successfully performed. The syntax for the simulation files was also explained and the method to create modules was also taught.

## **Part 1: Introduction to Circuit Design and SPICE simulations**

### **_What was learnt:_**

•	The importance of W/L ratio

•	Need of SPICE

•	NMOS design and specifications

- It is a four terminal deive
- It consists of a P-substrate body
- An isolation region created from SiO2 is present
- n+ diffusion region is present near the SiO2 layer
- It has a Gate oxide layer
- A Poly-Si or metal gate layer is added on top of the gate oxide layer
- There are a few abbreviations:
  - G means Gate
  - S means Source
  - D means Drain
  - B means Body or Bulk

![1631113926996](https://user-images.githubusercontent.com/89193562/132697108-70c1704e-7389-4d04-84c3-189d945e04d5.jpg)

Figure 1. The snap shot of an NMOS construction

•	Threshold Voltage (Vt)

  - The 'Vgs' voltage at which 'Strong Inversion' occurs is known as Threshold Voltage (Vt)

•	Concept of Strong Inversion

  - The phenomenon at which a part of the P-substrate becomes N-substrate (due to the high Vgs value) is called 'Strong Inversion'

•	Impact of Source-to-bulk Voltage (Vsb)

  - In presence of substrate bias voltage 'Vsb', an additional potential is required for strong inversion to occur

•	Threshold Voltage Equation

![Threshold voltage equation](https://user-images.githubusercontent.com/89193562/132532135-3de1b633-d02f-48b0-b9c6-030c40f2c30a.JPG)

where
  - Vto is the Threshold Voltage when Vsb = 0
  - Vto is a function of manufacturing voltage
  - ϒ is the body effect coefficient and it expresses the impact of changes in body bias 'Vsb' (unit of ϒ is V^0.5)
  - фf is the Fermi Potential

•	Body Effect Coefficient expression

![body effect coeffecient equation](https://user-images.githubusercontent.com/89193562/132532303-8b6fda87-3bc7-48ba-a99b-c7ffe5c4a969.JPG)

where
  - εsi is the relative permitivity of silicon (=11.7)
  - NA is the doping concentration
  - q is the charge of an electron
  - Cox is the oxide capacitance

•	Fermi Potential Equation

![fermi potential equation](https://user-images.githubusercontent.com/89193562/132532339-de5b4411-323e-48b2-bb3d-68b20e54dcef.JPG)

where
  - ni is the intrinsic doping parameter for the substrate


## **Part 2: NMOS Resistive region and Saturation region of operation**

### **_What was learnt:_**

•	Theory about Resistive region
  - It is also known as the Linear Region of operation
  - Since, Vgs=Vt, the changes that occur at different voltages of 'Vgs>Vt' are observed
  - In the channel, induced charge (Qi) α (Vgs-Vt)
  - The analysis is performed at Vgs=1V and a small (~0) Vds. Assume Vt=0.45V
  - In absence of Vds, the voltage across the n-channel was constant byt with application of Vds it is no more constant.
  - Let the effective channel length be L and 'x' axis be along the channel length and 'y' axis be perpendicular to the channel length
  - Let V(x) be the voltage at any point 'x' along the channel
  - Now, Vgs-V(x) is the gate-to-channel voltage at that point
  - Therefore, in the channel, induced charge at any point 'x' Qi(x) α - ((Vgs-V(x))-Vt)

•	Formula for charge induced at any point ‘x’

![induced charge at x](https://user-images.githubusercontent.com/89193562/132532646-03b38d68-de8d-45b1-92cf-7c240f922d2e.JPG)

•	First order analysis

•	Gate oxide capacitance formula

![gate oxide capacitance formula](https://user-images.githubusercontent.com/89193562/132532783-30c5d29d-4405-4833-a4b8-942d4787f50d.JPG)

where,
  - εox is the oxide permittivity = 3.97*εo = 3.5*10e-11 F/m
  - tox is the oxide thickness

•	The two kinds of current: Drift current and Diffusion current
  - Drift current is the current due to the potential difference
  - Diffusion current is the current due to difference in carrier concentration

•	The drift current (Id) = velocity of charge carriers * available charge over the channel width

![1631196789430](https://user-images.githubusercontent.com/89193562/132702310-fe28f367-775f-4e17-b28a-a3716fde099b.jpg)

Figure 2. The snap shot of top view of the MOSFET showing the channel width 'W'

•	Drift current (Id) formula

![drift current formula](https://user-images.githubusercontent.com/89193562/132532906-9238aba4-134e-4b1f-a00b-f7e126479071.JPG)

  - The term µn.Cox is denoted by kn' and kn' is known as process transconductance
  - kn'.(W/L) is denoted by kn and kn is also known as gain factor

•	Condition on Vds for the MOSFET to be in linear/resistive region or saturation/pinch-off region
  - When Vds <= (Vgs-Vt), the MOSFET is in linear region of operation
  - For this region, Id=kn.(Vgs-Vt).Vds as (Vds^2)/2 is a very small amount in this case
  - Vdds can be sweeped from 0V to (Vgs-Vt)V to make the device work in linear region of operation

•	Dependance of Id on Vds in pinch-off region
  - The chanel voltage is denoted with Vgs-Vds
  - Pinch-off condition is when Vgs-Vds=Vt
  - When the Pinch-off phenomenon is started, the channel begins to disappear. Basically, the channel starts to disappear only from the Drain side acquiring a triangular shape.
  - When Vgs-Vds<Vt, there is no channel present near the Drain terminal

![1631198852969](https://user-images.githubusercontent.com/89193562/132708164-64f39d56-8289-4af0-96c7-1e8515bc53fe.jpg)

Figure 3. The snap shot of the NMOS showing the pinch-off region

  - Id becomes (kn/2).(Vgs-Vt)^2
  - It looks like a perfect current source i.e current is constant. It is not true because effective conductive channel length is modulated by applied Vds.
  - As Vds increases, the depletion region at the drain terminal increases and hence, the effective channel length decreases.
 
- Now the Drain current equation becomes:

![Id pinch off](https://user-images.githubusercontent.com/89193562/132710166-0b0c76d9-aeab-4a32-b56a-3ec5678c0fa6.JPG)

- Here, λ is the channel length modulation

## **Part 3: Introduction to SPICE**

### **_What was learnt:_**

•	SPICE model parameters

•	SPICE simulation flow diagram

![spice workflow](https://user-images.githubusercontent.com/89193562/132533155-7affa537-beb3-4aa4-8eab-b4ff3aaab64d.JPG)

•	SPICE netlist for our NMOS

•	Definition of nodes and the method to identify them

•	SPICE syntax

•	Method to save SPICE model

•	Method to write code for SPICE simulation

### **_Lab Activity:_**

![day1 ngspice command](https://user-images.githubusercontent.com/89193562/132533223-85fac5e7-3073-43fc-9d14-a248e9116a2e.JPG)

Figure 4. The snap shot of the terminal window for Day1 activity

![1631113614117](https://user-images.githubusercontent.com/89193562/132535503-e272eee6-35b4-4763-832c-367f36209678.jpg)

Figure 5. The snap shot of SPICE netlist of the above NMOS

![day1 spice model](https://user-images.githubusercontent.com/89193562/132533338-e2298388-5d87-49a2-b5e2-6156ce69c46d.JPG)

Figure 6. The snap shot of the output window of the Day1 activity


# **Day 2: Velocity Saturation and basics of CMOS inverter VTC**

On the second day of the workshop SPICE simulation for lower nodes and the characteristics for long channel and short channel devices were observed. Also, the velocity saturation at lower and higher electric fields and velocity saturation drain current model were observed.

Finally MOSFET as a switch and the characteristics of CMOS inverter were taught.

## **Part 1: SPICE simulation for lower nodes and velocity saturation effect**

### **_What was learnt:_**

•	The distribution of various regions of operation of NMOS over the graph plotted between Ids and Vds.

![plot (0)](https://user-images.githubusercontent.com/89193562/132674785-f6e3444f-2e00-45d9-ac47-7f4c8e040074.png)

Figure 7. The snap shot of various regions of operation of NMOS on graph plotted between Ids and Vds.


•	The theory about cut-off region of NMOS.

•	Short channel effect

•	Velocity Saturation effect

![velocity saturation equation](https://user-images.githubusercontent.com/89193562/132674315-002da47e-65d4-4976-b2c0-b309dee76df7.JPG)

![velocity saturation graph JPG](https://user-images.githubusercontent.com/89193562/132679374-baa32830-fcca-49c3-be54-10b5caf2c5d3.png)

Figure 8. The snap shot of the graph of velocity saturation effect

•	The modes of operation for long channel (>250nm) devices and short channel (<250nm) devices.

•	The equation of Id for long channel and short channel devices

![Id equation](https://user-images.githubusercontent.com/89193562/132674348-c1e9e289-f766-4750-94f1-eb4cfe5189eb.JPG)

•	The various modes when the value of Vmin is different

•	Velocity Saturation causes device to saturate early

### **_Lab Activity:_**

![ngspice command window with vgs sweep](https://user-images.githubusercontent.com/89193562/132675164-206b1eeb-8cba-44a8-af4f-bf4322e37550.JPG)

Figure 9. The snap shot of terminal window for plot between Ids and Vds for short channel device

![plot window with vgs sweep](https://user-images.githubusercontent.com/89193562/132675399-e8f69dc7-f222-4e91-81fc-4cb2639213d4.JPG)

Figure 10. The snap shot of output window for plot between Ids and Vds for short channel device

![ngspice Id vs Vgs curve command window](https://user-images.githubusercontent.com/89193562/132675473-18cd0d22-a956-4c4a-978b-e4837c292d70.JPG)

Figure 11. The snap shot of terminal window for plot between Ids and Vds for short channel device without the sweep for vdd

![plot window Id vs Vgs](https://user-images.githubusercontent.com/89193562/132675655-f779b9be-bcee-4d31-8a62-6204bc0bca40.JPG)

Figure 12. The snap shot of output window for plot between Ids and Vds for short channel device without the sweep for vdd

## **Part 2: CMOS voltage transfer characteristics (VTC)**

### **_What was learnt:_**

•	Transistor as a switch

•	The working of CMOS

•	What happens when Vin is ‘high’ and equal to ‘vdd’ and what happens when Vin is ‘low’ and equal to ‘0V’

•	The flow of current when Vin is ‘high’ and when Vin is ‘low’

•	Defined terminologies in CMOS inverter

![1631186540042](https://user-images.githubusercontent.com/89193562/132681895-fe353e35-c49a-4fcf-a822-640a20898861.jpg)

Figure 13. The snap shot of the circuit diagram of CMOS inverter

•	By observation:

- For the NMOS voltage equations

![NMOS relations](https://user-images.githubusercontent.com/89193562/132678807-2bcbfa75-4081-46cb-899d-7b3915c62688.JPG)

- For the PMOS voltage equations

![PMOS relations](https://user-images.githubusercontent.com/89193562/132678852-68fd02e7-f396-45f5-8ea3-3b2645c71372.JPG)

- For the relationship between the currents

![current relations](https://user-images.githubusercontent.com/89193562/132678900-8087d81b-0588-46f8-8fc9-11e51725ebdd.JPG)

•	Load curve for PMOS transistor in CMOS inverter

![PMOS load curve](https://user-images.githubusercontent.com/89193562/132680045-00315560-5c42-4a80-a93a-6b28f645eca7.png)

Figure 14. The snap shot of load curve for PMOS transistor in CMOS inverter

•	Load curve for NMOS transistor in CMOS inverter

![NMOS load curve](https://user-images.githubusercontent.com/89193562/132680062-e4b6e546-8e41-4108-bf3f-39eb6946a5c7.png)

Figure 15. The snap shot of load curve for NMOS transistor in CMOS inverter

•	Superimposing the load curve of NMOS on the load curve of PMOS and plotting Vin vs Vout from the graph obtained

![overlap](https://user-images.githubusercontent.com/89193562/132680555-d5eeedda-33ba-4d71-b885-c8779c9d0b50.JPG)

Figure 16. The snap shot of superimposed load curve of NMOS and load curve of PMOS

![vin vs vout](https://user-images.githubusercontent.com/89193562/132681467-4b755f7f-3e0b-4f90-bad5-c2bcaac6fded.png)

Figure 17. The snap shot of the plot of Vout versus Vin
