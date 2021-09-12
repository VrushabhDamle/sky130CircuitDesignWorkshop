# CMOS Circuit Design and SPICE Simulation using SKY130 Technology Workshop

![CMOS-Workshop-Banner](https://user-images.githubusercontent.com/89193562/132950141-4135f3d2-5ec6-477f-899c-3c307ddcaf1d.jpg)

### **_Brief Description of the course_**
This is a five-day workshop focused towards CMOS circuit design and SPICE simulation using SKY130 technology organized by [VLSI System Design]( https://www.vlsisystemdesign.com/). The content of the workshop is divided across the five days in a smart way which allows the learner to grasp all the concepts if the workshop is attended dedicatedly. On the first day of the workshop the emphasis was on the basics of NMOS Drain current (Id), Drain-to-source Voltage (Vds) and the plot between the two of them. The second day focusses primarily on velocity saturation and basics of CMOS inverter VTC and the plots between Id and Vgs and the plot for determining the value of Vt. The third was concentrated on CMOS switching threshold and dynamic simulations, where a lot of equations were derived to find the relationships between the (W/L) ratios of the PMOS and NMOS and the switching threshold voltage (Vm). On the fourth day of the workshop, Noise margins and CMOS inverter robustness with respect to them was discussed. On the fifth and final day of the workshop the emphasis was on Power supply variation and Device variation. In the power supply variation, the effects of using various power supplies on the inverter were observed and we discussed the advantages and disadvantages of using small power supply and the reason that it is not used. In the device variation, the impact of manufacturing processes on a single inverter and inverter chain were discussed.

# **_INDEX:_**
- [CMOS Circuit Design and SPICE Simulation using SKY130 Technology Workshop](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#cmos-circuit-design-and-spice-simulation-using-sky130-technology-workshop)
    - [Brief Description of the course](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#brief-description-of-the-course)
- [INDEX](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#index)
- [Day 1: Basics of NMOS Drain Current (Id) vs Drain-to-source Voltage (Vds)](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#day-1-basics-of-nmos-drain-current-id-vs-drain-to-source-voltage-vds)
  - [Part 1: Introduction to Circuit Design and SPICE simulations](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#part-1-introduction-to-circuit-design-and-spice-simulations)
      - [What was learnt](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#what-was-learnt)
  - [Part 2: NMOS Resistive region and Saturation region of operation](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#part-2-nmos-resistive-region-and-saturation-region-of-operation)
      - [What was learnt](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#what-was-learnt-1)
  - [Part 3: Introduction to SPICE](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#part-3-introduction-to-spice)
      - [What was learnt](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#what-was-learnt-2)
      - [Lab Activity](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#lab-activity)
- [Day 2: Velocity Saturation and basics of CMOS inverter VTC](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#day-2-velocity-saturation-and-basics-of-cmos-inverter-vtc)
    - [Part 1: SPICE simulation for lower nodes and velocity saturation effect](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#part-1-spice-simulation-for-lower-nodes-and-velocity-saturation-effect)
        - [What was learnt](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#what-was-learnt-3)
        - [Lab Activity](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#lab-activity-1)
    - [Part 2: CMOS voltage transfer characteristics (VTC)](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#part-2-cmos-voltage-transfer-characteristics-vtc)
        - [What was learnt](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#what-was-learnt-4)
- [Day 3: CMOS switching threshold and dynamic simulations](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#day-3-cmos-switching-threshold-and-dynamic-simulations)
    - [Part 1: Voltage transfer characteristics and SPICE simulations](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#part-1-voltage-transfer-characteristics-and-spice-simulations)
        - [What was learnt](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#what-was-learnt-5)
        - [Lab Activity](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#lab-activity-2)
    - [Part 2: Static Behavior Evaluation - CMOS Inverter Robustness: Switching threshold](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#part-2-static-behavior-evaluation---cmos-inverter-robustness-switching-threshold)
        - [What was learnt](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#what-was-learnt-6)
- [Day 4: CMOS Noise Margin Robustness Evaluation](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#day-4-cmos-noise-margin-robustness-evaluation)
    - [Part 1: Static Behavior Evaluation - CMOS Inverter Robustness: Noise Margin](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#part-1-static-behavior-evaluation---cmos-inverter-robustness-noise-margin)
        - [What was learnt](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#what-was-learnt-7)
        - [Lab Activity](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#lab-activity-3)
- [Day 5: CMOS Power supply and device variation robustness evaluation](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#day-5-cmos-power-supply-and-device-variation-robustness-evaluation)
    - [Part 1: Static Behavior Evaluation - CMOS Inverter Robustness: Power Supply Variation](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#part-1-static-behavior-evaluation---cmos-inverter-robustness-power-supply-variation)
        - [What was learnt](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#what-was-learnt-8)
        - [Lab Activity](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#lab-activity-4)
    - [Part 2: Static Behavior Evaluation - CMOS Inverter Robustness: Device Variation](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#part-2-static-behavior-evaluation---cmos-inverter-robustness-device-variation)
        - [What was learnt](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#what-was-learnt-9)
        - [Lab Activity](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#lab-activity-5)
- [Conclusion](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#conclusion)
- [References](https://github.com/VrushabhDamle/sky130CircuitDesignWorkshop/blob/main/README.md#references)
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

- The spice waveforms can be used to calculate the delay of a cell. These delays are very close to the practical delays observed.

-	SPICE model parameters

-	SPICE simulation flow diagram

![spice workflow](https://user-images.githubusercontent.com/89193562/132533155-7affa537-beb3-4aa4-8eab-b4ff3aaab64d.JPG)

-	SPICE netlist for our NMOS

![1631113614117](https://user-images.githubusercontent.com/89193562/132711027-1aa941dc-56bc-4be9-af32-5a96b76d9c09.jpg)

Figure 4. The snap shot of SPICE netlist of the above NMOS

- R1 resistance is added as it is not desired that the current from Vin would be directly fed to the gate of M1.

-	Definition of nodes and the method to identify them
    - A node is can be defined as a point connecting two termials. If two terminals of a single device are short circuited then the node is said to be in between these two terminals. But most of the times a node connects two different devices.
    - The method to identify nodes is to identify the SPICE netlist for the device and all the wires connecting different components have one node on them.

-	SPICE syntax

-	Method to save SPICE model

-	Method to write code for SPICE simulation

### **_Lab Activity:_**

For performing the Day 1 Lab activity we need the following code:
```
*Model Description
.param temp=27

*Including sky130 library files
.lib "sky130_fd_pr/models/sky130.lib.spice" tt

*Netlist Description

XM1 Vdd n1 0 0 sky130_fd_pr__nfet_01v8 w=5 l=2
R1 n1 in 55
Vdd vdd 0 1.8V
Vin in 0 1.8V

*simulation commands

.op
.dc Vdd 0 1.8 0.1 Vin 0 1.8 0.2

.control

run
display
setplot dc1
.endc

.end
```

- There are five types of process corners available for use:
    - tt -> Typical corner
    - sf -> Slow-fast corner
    - ff -> Fast-fast corner
    - ss -> Slow-slow corner
    - fs -> Fast-slow corner
- In the Lab activity, tt corner is used. The corner can be changed by changing the word 'tt' in the line `.lib "sky130_fd_pr/models/sky130.lib.spice" tt` with any valid process corner

![day1 ngspice command](https://user-images.githubusercontent.com/89193562/132533223-85fac5e7-3073-43fc-9d14-a248e9116a2e.JPG)

Figure 5. The snap shot of the terminal window for Day1 activity

![day1 spice model](https://user-images.githubusercontent.com/89193562/132533338-e2298388-5d87-49a2-b5e2-6156ce69c46d.JPG)

Figure 6. The snap shot of the output window of the Day1 activity

- To observe the value of Id at any point on the curve, then left click on the point on the curve to be observed.
- Now on the terminal window, some values of x0 and y0 should appear.
- The value of Id corresponds to the value of y0 in ampere.

# **Day 2: Velocity Saturation and basics of CMOS inverter VTC**

On the second day of the workshop SPICE simulation for lower nodes and the characteristics for long channel and short channel devices were observed. Also, the velocity saturation at lower and higher electric fields and velocity saturation drain current model were observed.

Finally MOSFET as a switch and the characteristics of CMOS inverter were taught.

## **Part 1: SPICE simulation for lower nodes and velocity saturation effect**

### **_What was learnt:_**

•	The distribution of various regions of operation of NMOS over the graph plotted between Ids and Vds.

![regions of operation](https://user-images.githubusercontent.com/89193562/132864852-2f667ae5-a71c-4e67-975a-e4c137843114.png)

Figure 7. The snap shot of various regions of operation of NMOS on graph plotted between Ids and Vds.

- The plot overlapping with the 'x' axis is at Vgs=0V and that is because there is 0 drain current at that point of time and the reason is that when Vgs=0V the nmos is not turned 'ON' so, there is no channel present.

-	The theory about cut-off region of NMOS.
    - When Vgs<Vt the region of operation of the NMOS is said to be the cut-off region
    - Cut-off region is a region where the device has been cut-off or it is 'OFF'

-	Short channel effect

-	Velocity Saturation effect
    - For the lower values of electric field, the velocity tends to be a linear function of the electric field. But, after a certain point (cut-off) the velocity just saturates. This point of saturation is represented by εc (critical electric field)
    - Vn(m/S) = linear for ε<=εc
    - Vn(m/S) = constant for ε>=εc

![velocity saturation equation](https://user-images.githubusercontent.com/89193562/132674315-002da47e-65d4-4976-b2c0-b309dee76df7.JPG)

![velocity saturation graph JPG](https://user-images.githubusercontent.com/89193562/132679374-baa32830-fcca-49c3-be54-10b5caf2c5d3.png)

Figure 8. The snap shot of the graph of velocity saturation effect

-	The modes of operation for long channel (>250nm) devices and short channel (<250nm) devices.
-	The modes of operation for long channel devices are:
    - Cut-off region
    - Resistive region
    - Saturation region
- The modes of operation for short channel devices are:
    - Cut-off region
    - Resistive region
    - Velocity Saturation region
    - Saturation region
 
- Let's call (Vgs-Vt)=Vgt

-	The equation of Id for long channel and short channel devices

![Id equation](https://user-images.githubusercontent.com/89193562/132674348-c1e9e289-f766-4750-94f1-eb4cfe5189eb.JPG)

- Vdsat is a technology parameter saturation voltage i.e voltage at which device velocity saturates and is independent of Vgs or Vds

-	The various modes when the value of Vmin is different
    - When Vgt is the minimum of Vgt, Vds, Vdsat the device is in saturation region.
    - When Vds is the minimum of Vgt, Vds, Vdsat the device is in resistive region.
    - When Vdsat is the minimum of Vgt, Vds, Vdsat the device is in velocity saturation region.
    - It looks like current should increase at lower nodes.

-	Velocity Saturation causes device to saturate early

### **_Lab Activity:_**

For plotting the graph between Ids and Vds for short channel devices we need to write the following SPICE code:
```
*Model Description
.param temp=27

*Including sky130 library files
.lib "sky130_fd_pr/models/sky130.lib.spice" tt

*Netlist Description

XM1 Vdd n1 0 0 sky130_fd_pr__nfet_01v8 w=0.39 l=0.15
R1 n1 in 55

Vdd vdd 0 1.8V
Vin in 0 1.8V

*simulation commands

.op
.dc Vdd 0 1.8 0.1 Vin 0 1.8 0.2

.control

run
display
setplot dc1
.endc

.end
```

![ngspice command window with vgs sweep](https://user-images.githubusercontent.com/89193562/132675164-206b1eeb-8cba-44a8-af4f-bf4322e37550.JPG)

Figure 9. The snap shot of terminal window for plot between Ids and Vds for short channel device

![plot window with vgs sweep](https://user-images.githubusercontent.com/89193562/132675399-e8f69dc7-f222-4e91-81fc-4cb2639213d4.JPG)

Figure 10. The snap shot of output window for plot between Ids and Vds for short channel device

- To observe the value of Id at any point on the curve, then left click on the point on the curve to be observed.
- Now on the terminal window, some values of x0 and y0 should appear.
- The value of Id corresponds to the value of y0 in ampere.

To calculate Threshold voltage for Id versus Vgs curve, the following SPICE code is required:
```
*Model Description
.param temp=27

*Including sky130 library files
.lib "sky130_fd_pr/models/sky130.lib.spice" tt

*Netlist Description
XM1 Vdd n1 0 0 sky130_fd_pr__nfet_01v8 w=0.39 l=0.15
R1 n1 in 55

Vdd vdd 0 1.8V
Vin in 0 1.8V

*simulation commands

.op
.dc Vin 0 1.8 0.1

.control

run
display
setplot dc1
.endc

.end

```

![ngspice Id vs Vgs curve command window](https://user-images.githubusercontent.com/89193562/132675473-18cd0d22-a956-4c4a-978b-e4837c292d70.JPG)

Figure 11. The snap shot of terminal window for plot between Ids and Vds for short channel device without the sweep for vdd

![plot window Id vs Vgs](https://user-images.githubusercontent.com/89193562/132675655-f779b9be-bcee-4d31-8a62-6204bc0bca40.JPG)

Figure 12. The snap shot of output window for plot between Ids and Vds for short channel device without the sweep for vdd

- In order to calculate the Threshold voltage, the linear part of the plot must be extended. Now, the x intercept of this extended plot gives the value of the threshold voltage of the device that is being simulated.

## **Part 2: CMOS voltage transfer characteristics (VTC)**

### **_What was learnt:_**

-	Transistor as a switch
    - With infinite 'Off' resistance when |Vgs|<|Vt|
    - With finite 'On' resistance when |Vgs|>|Vt|

-	The working of CMOS inverter

-	What happens when Vin is ‘high’ and equal to ‘vdd’
    - PMOS turns 'OFF'
    - NMOS turns 'ON'
   
-  What happens when Vin is ‘low’ and equal to ‘0V’
    - PMOS turns 'ON'
    - NMOS turns 'OFF'

-	The flow of current when Vin is ‘high’ and when Vin is ‘low’
- When Vin=Vdd
    - Direct path exists between Vout and Vss resulting in Vout=0V
- When Vin=0V
    - Direct path exists between Vdd and Vout, resulting in Vout=Vdd

-	Defined terminologies in CMOS inverter

![1631186540042](https://user-images.githubusercontent.com/89193562/132681895-fe353e35-c49a-4fcf-a822-640a20898861.jpg)

Figure 13. The snap shot of the circuit diagram of CMOS inverter

-	By observation:
- For the NMOS voltage equations

![NMOS relations](https://user-images.githubusercontent.com/89193562/132678807-2bcbfa75-4081-46cb-899d-7b3915c62688.JPG)
    
- For the PMOS voltage equations

![PMOS relations](https://user-images.githubusercontent.com/89193562/132678852-68fd02e7-f396-45f5-8ea3-3b2645c71372.JPG)

- For the relationship between the currents

![current relations](https://user-images.githubusercontent.com/89193562/132678900-8087d81b-0588-46f8-8fc9-11e51725ebdd.JPG)

-	Load curve for PMOS transistor in CMOS inverter

![1631302325727](https://user-images.githubusercontent.com/89193562/132907643-9423cede-796e-40b7-a8bb-36fde16d533f.jpg)

Figure 14. The snap shot of load curve for PMOS transistor in CMOS inverter

-	Load curve for NMOS transistor in CMOS inverter

![1631302325723](https://user-images.githubusercontent.com/89193562/132907688-664d7f0e-da4e-4c36-9270-fca25f24b945.jpg)

Figure 15. The snap shot of load curve for NMOS transistor in CMOS inverter

-	Superimposing the load curve of NMOS on the load curve of PMOS and plotting Vin vs Vout from the graph obtained

![1631359704747](https://user-images.githubusercontent.com/89193562/132946435-09010251-dd7e-4af4-b791-ea5655dd171f.jpg)

Figure 16. The snap shot of superimposed load curve of NMOS and load curve of PMOS

![1631278404895](https://user-images.githubusercontent.com/89193562/132859275-865ad5a6-d174-4bb0-9615-77cc5deb9992.jpg)

Figure 17. The snap shot of the plot of Vout versus Vin

- Graphically, the Vin points from the intersection of corresponding load lines are picked-up.

# **Day 3: CMOS switching threshold and dynamic simulations**

On the third day of the workshop the emphasis was on Voltage Transfer Characteristics using SPICE simulations and later on CMOS Inverter Robustness. Many factors were told but only the switching threshold was discussed in depth. An equation relating switching threshold voltage (Vm) and (W/L) ratios of the PMOS and the NMOS was also derived and alternatively, an equation for (W/L) ratios of the PMOS and the NMOS if the Vm is preset was also derived.

## **Part 1: Voltage transfer characteristics and SPICE simulations**

### **_What was learnt:_**
- The various components of a SPICE deck:
    - Component connectivity
    - Component values
    - Identification of 'nodes'
    - Naming 'nodes'

- Let us consider the following SPICE netlist

![1631280484301](https://user-images.githubusercontent.com/89193562/132860957-9e9492b5-c646-4866-add5-279064e73c82.jpg)

Figure 18. The snap shot of the SPICE netlist considered

- The SPICE code for the above netlist looks something like following:
```
***MODEL Description***
***NETLIST Description***
M1 out in vdd vdd pmos W=0.375u L=0.25u
M2 out in  0   0  nmos W=0.375u L=0.25u

cload out 0 10f

Vdd vdd 0 2.5
Vin  in 0 2.5

***SIMULATION Commands***
.op
.dc Vin 0 2.5 0.05

***.include tsmc_025um_model.mod***
.LIB "tsmc_025um_model.mod" CMOS_MODELS
.end
```

### **_Lab Activity:_**

For plotting the Vtc characteristics of CMOS inverter, the following code is needed:
```
*Model Description
.param temp=27

*Including sky130 library files
.lib "sky130_fd_pr/models/sky130.lib.spice" tt

*Netlist Description

XM1 out in vdd vdd sky130_fd_pr__pfet_01v8 w=0.84 l=0.15
XM2 out in 0 0 sky130_fd_pr__nfet_01v8 w=0.36 l=0.15

Cload out 0 50fF

Vdd vdd 0 1.8V
Vin in 0 1.8V

*simulation commands

.op

.dc Vin 0 1.8 0.01

.control
run
setplot dc1
display
.endc

.end
```

![terminal window out vs in](https://user-images.githubusercontent.com/89193562/132863150-3d5b53a2-a802-43cd-aaca-1d28bca51945.JPG)

Figure 19. The snap shot of the terminal window for plotting the Vtc characteristics of CMOS inverter

![output window out vs in](https://user-images.githubusercontent.com/89193562/132863366-e80c7b36-42af-45bb-a140-c75502008046.JPG)

Figure 20. The snap shot of the output window for plotting the Vtc characteristics of CMOS inverter

- To find the switching threshold voltage (Vm), it is known that Vout = Vin so zoom in on the plot where roughly Vout = Vin by selecting the area of the plot by right clicking on the screen and dragging it to select the area.
- Zoom twice or thrice until the point where Vm lies becomes almost certain.
- Left click roughly on the point on the curve where Vm should approximately lie.
- Values of x0 and y0 will now appear on the terminal window.
- Since we are finding Vm, therefore x0 ~ y0 and hence x0=y0=Vm.


For performing the transient analysis, the following code is required:
```
*Model Description
.param temp=27

*Including sky130 library files
.lib "sky130_fd_pr/models/sky130.lib.spice" tt

*Netlist Description

XM1 out in vdd vdd sky130_fd_pr__pfet_01v8 w=0.84 l=0.15
XM2 out in 0 0 sky130_fd_pr__nfet_01v8 w=0.36 l=0.15

Cload out 0 50fF

Vdd vdd 0 1.8V
Vin in 0 PULSE(0V 1.8V 0 0.1ns 0.1ns 2ns 4ns)

*simulation commands

.tran 1n 10n

.control
run
.endc

.end
```

![terminal window transient](https://user-images.githubusercontent.com/89193562/132863836-2348a72e-a7e9-4ee3-9d3c-bb5c63d64183.JPG)

Figure 21. The snap shot of the terminal window for performing the transient analysis

![output window transient](https://user-images.githubusercontent.com/89193562/132863939-9f777f44-e10e-4bc3-a9a2-41e833dd465b.JPG)

Figure 22. The snap shot of the output window for performing the transient analysis

- To calculate the rise delay:
    - Zoom on the part of the curve having fall of the input pulse and rise of the output pulse around voltage of (Vdd/2) by right clicking on the screen and dragging it to select the area.
    - Now, left click on the rising edge of the output curve at (Vdd/2) to get a point x0,y0 on the terminal.
    - Similarly, get the point at (Vdd/2) for falling edge of the input curve.
    - The difference between the x-coordinate of the rising edge of the output curve and the falling edge of the input curve is the rise delay.
- To calculate the falling delay:
    - Zoom on the part of the curve having rise of the input pulse and fall of the output pulse around voltage of (Vdd/2) by right clicking on the screen and dragging it to select the area.
    - Now, left click on the falling edge of the output curve at (Vdd/2) to get a point x0,y0 on the terminal.
    - Similarly, get the point at (Vdd/2) for rising edge of the input curve.
    - The difference between the x-coordinate of the falling edge of the output curve and the rising edge of the input curve is the fall delay.

## **Part 2: Static Behavior Evaluation - CMOS Inverter Robustness: Switching threshold**

### **_What was learnt:_**

- CMOS inverter is a robust device because the shape of it's input versus output curve remains the same for all different values of (W/L) ratios.
- Static Behavior Evaluation: CMOS Inverter Robustness
    - Switching Threshold
    - Noise Margin
    - Power Supply Variation
    - Device Variation

- Switching Threshold (Vm)
    - It is the point where Vin = Vout
    - Graphical method to find Vm is to draw a line across the graph of output voltage to input voltage of a CMOS inverter starting at the origin and ending at the opposite diagonal of the plot (basically a line with a 45 degree inclination with the x-axis). Now, the x-coordinate of the point of intersection of this line and the curve is the switching threshold.
    - Vm when (Wp/Lp) is 1.5 is approximately equal to 0.98V and when (Wp/Lp) is 3.75 it is approximately equal to 1.2V
    - Wp and Lp in the above section are Width of PMOS channel and Length of PMOS channel
    - At Vm, both PMOS and NMOS are turned 'ON' because Vgs almost crossed the threshold region for both of them.
    - A few observations can be made from the information stated above,
    - Therefore, Vgs = Vds
    - IdsP = - IdsN which means that IdsP + IdsN = 0
    - We know the equations for IdsN and IdsP which are as stated below:
    
      ![Idsn and Idsp equations](https://user-images.githubusercontent.com/89193562/132867914-dc5b1ac9-a4d9-452b-9352-4872c94264fe.JPG)

We ignore the 1+λVds because the term is very small and it makes the equations very difficult for hand calculations.

Since, IdsP + IdsN = 0

Therefore, the equations can be re-written as:

![Idsn_plus_Idsp_is_zero](https://user-images.githubusercontent.com/89193562/132868215-8eb427a0-1a5a-4c3f-8cd5-76c41d49d947.JPG)

Let's consider this as equation 1

Solving the above equation for Vm,

![vm equation](https://user-images.githubusercontent.com/89193562/132869184-bd60ea34-e16f-4c7b-9be7-05386549329a.JPG)

- Alternatively, the required ratio of PMOS versus NMOS transistor size can be derived such that Vm is set.

Equation 1 must be taken in the form IdsN = - IdsP

Therefore,

![wp lp wn ln equation](https://user-images.githubusercontent.com/89193562/132872201-eba019d8-5a72-480a-a44d-f4d66f718da1.JPG)

- Here,
    - Wp is the width of the channel in PMOS
    - Lp is the length of the channel in PMOS
    - Wn is the width of the channel in NMOS
    - Ln is the length of the channel in NMOS
    - kn' is the process transconductance of the NMOS
    - kp' is the process transconductance of the PMOS
    - Vdsatn is the Vdsat of the NMOS
    - Vdsatp is the Vdsat of the PMOS
    - Vm is the switching threshold voltage
    - Vt is the threshold voltage
    - Vdd is the supply voltage

- We experimented with the sizes of the PMOS with respect to the sizes of NMOS and came up with the following conclusions

|(Wp/Lp)|x.(Wn/Ln)|Rise Delay|Fall Delay|Vm   |
|:---:  |:---:    |:---:     |:---:     |:---:|
|(Wp/Lp)|1.(Wn/Ln)|148pS     |71pS      |0.99V|
|(Wp/Lp)|2.(Wn/Ln)|80pS      |76pS      |1.2V |
|(Wp/Lp)|3.(Wn/Ln)|57pS      |80pS      |1.25V|
|(Wp/Lp)|4.(Wn/Ln)|45pS      |84pS      |1.35V|
|(Wp/Lp)|5.(Wn/Ln)|37pS      |88pS      |1.4V |

- We can make some conclusions from the above table:
    - When `(Wp/Lp) = 2.(Wn/Ln)`, there is an approximately equal rise-fall delay
    - Due to the equal rise-fall delay, `(Wp/Lp) = 2.(Wn/Ln)` create typical characteristics for a clock inverter/buffer
    - The conditions other than `(Wp/Lp) = 2.(Wn/Ln)` can still be used as regular inverters/buffers and these can be preferred for data path
    - Switching Threshold for `(Wp/Lp) = 2.(Wn/Ln)` and `(Wp/Lp) = 3.(Wn/Ln)` is very small. Similarly, switching threshold for `(Wp/Lp) = 4.(Wn/Ln)` and `(Wp/Lp) = 5.(Wn/Ln)` is also very small

- When Wp/Lp is increased, the rise delay is isgnificantly reduced because time required for the output capacitor to charge decreases significantly and the reason is the availability of a bigger area to charge the capacitor.
- Ron(PMOS) ~ 2.5\*Ron(NMOS)

# **Day 4: CMOS Noise Margin Robustness Evaluation**

On the fourth day of the workshop, the robustness of a CMOS inverter in terms of noise margins was demonstrated. We learned the concept of noise margins, the different noise margin ranges and the concepts of Voh, Vih, Vil and Vol. Finally, equations of Noise Margin High (NMh) and Noise Margin Low (NMl) were derived in terms of Voh, Vih, Vil and Vol. During the lab activity, the Noise Margins were found for an inverter with (Wp/Lp) = (2.77).(Wn/Ln)

## **Part 1: Static Behavior Evaluation - CMOS Inverter Robustness: Noise Margin**

### **_What was learnt:_**

- The ideal and actual Input-Output characteristics of an inverter were observed

![1631346101863](https://user-images.githubusercontent.com/89193562/132940629-2c46f46d-d9a6-4c3b-9615-45f88bac7944.jpg)

Figure 23. The snap shot of the ideal Input-Output characteristics of an Inverter

![1631345938506](https://user-images.githubusercontent.com/89193562/132940634-1688436a-cf57-41d7-82d8-70e0512a1154.jpg)

Figure 24. The snap shot of the actual Input-Output characteristics of an Inverter with finite slope

- In the above diagram, the terms stated are explained as follows:
    - Vil is Input Low Voltage (Vil could be Vdd/4)
        - Any input voltage level between 0 and Vil will be treated as logic '0'
    - Voh is Output High Voltage (Vih < Voh <= Vdd)
        - Any output voltage level between Voh and Vdd will be treated as logic '1'
    - Vih is Input High Voltage (Vih could be 3.Vdd/4)
        - Any input voltage level between Vih and Vdd will be treated as logic '1'
    - Vol is Output Low Voltage (0 <= Vol < Vil)
        - Any output voltage level between 0 and Vol will be treated as logic '0'
- Actual Input-Output characteristics on an inverter were observed and they were plotted on a scale

![1631346891597](https://user-images.githubusercontent.com/89193562/132940893-994a25d6-d89f-401f-b98f-868a4f438ef1.jpg)

Figure 25. The snap shot of the actual Input-Output characteristics of an Inverter

![1631346891586](https://user-images.githubusercontent.com/89193562/132940899-e462e34a-643c-4864-9024-73bc997474c1.jpg)

Figure 26. The snap shot of the Input-Output characteristics of an Inverter plotted on a scale

- In the above diagram, the terms stated are explained as follows:
    - NMh is the Noise Margin High
        - Any voltage level in "NMh" range will be detected as logic '1'
    - NMl is the Noise Margin Low
        - Any voltage level in "NMl" range will be detected as logic '0'
    - Undefined region
        - Any signal in "Undefined region" will be an indefinite logic level
- Noise Margins are the tolerance levels of the noise
- The equations for NMh and NMl are as follows:

![nmh and nml equations](https://user-images.githubusercontent.com/89193562/132941048-4d1a35eb-24bc-44dd-ba25-5a5abecd73bb.JPG)

- Now with the voltage levels plotted in the noise margin scale, we have prepared a chart that will give the summary of the noise margin:

![1631370670487](https://user-images.githubusercontent.com/89193562/132951411-2ce7e449-b8bb-4e24-90b3-932e3344533d.jpg)

Figure 27. The snap shot of the Noise induced bump characteristics at different noise margin levels

- For any signal to be considered as logic '0' and logic '1', it should be in the NMl and NMh ranges, respectively.
        - If the height of the bump lies in between Vol and Vil then it's not hazardous because it still lies in the range of logic '0'. Any glitch that occurs in this region is a safe glitch because it will still be considered as logic '0'.
        - If the height of the bump lies in the "undefined region" then it is potentially hazardous because it can acquire logic '1' which can be fatal. Any glitch in this region is unsafe because it is unclear if it will go to logic '1' or fall to logic '0'.
        -  If the height of the bump lies in between Vih and Voh then it will definitely be considered as logic '1'. These kinds of glitches are the glitches that need to be fixed.
- The noise margins of the inverter at different values of Wp/Lp were observed and they were as follows:

|(Wp/Lp)|x.(Wn/Ln)|NMh       |NMl       |Vm   |
|:---:  |:---:    |:---:     |:---:     |:---:|
|(Wp/Lp)|1.(Wn/Ln)|0.3       |0.3       |0.99V|
|(Wp/Lp)|2.(Wn/Ln)|0.35      |0.3       |1.2V |
|(Wp/Lp)|3.(Wn/Ln)|0.4       |0.3       |1.25V|
|(Wp/Lp)|4.(Wn/Ln)|0.42      |0.27      |1.35V|
|(Wp/Lp)|5.(Wn/Ln)|0.42      |0.27      |1.4V |

- A few conclusions can be inferred from the above table:
        - When `(Wp/Lp) = 2.(Wn/Ln)` there is a rise at the NMh because PMOS is responsible for holding the charges on the capacitance. When the size of PMOS is increased, a low-resistance path from supply to the capacitance is formed and as a result of that, the capacitance is able to retain the charge for a longer amount of time resulting in an increased NMh.
        - When `(Wp/Lp) = 4.(Wn/Ln)` there is a drop at the NMl because the NMOS has now become weaker than the PMOS
        - When `(Wp/Lp) = 5.(Wn/Ln)` the NMh almost comes to a static point.
        - In the above table, NMl is not affected much but NMh has increased by 120mV but this range is still acceptable and this proves the CMOS inverter robustness with respect to the Noise Margin.
        - Finally, the areas that can be used for digital and analog applications are stated in the figure below:

![1631370670492](https://user-images.githubusercontent.com/89193562/132952201-c0a046b8-1c7e-45f3-bd8e-590efba51f59.jpg)

Figure 28. The snap shot of the Vout versus Vin curve showing the areas that can be used for digital and analog applications

### **_Lab Activity:_**

For performing the Day 4 Lab Activity we need the following code
```
*Model Description
.param temp=27

*Including sky130 library files
.lib "sky130_fd_pr/models/sky130.lib.spice" tt

*Netlist Description

XM1 out in vdd vdd sky130_fd_pr__pfet_01v8 w=1 l=0.15
XM2 out in 0 0 sky130_fd_pr__nfet_01v8 w=0.36 l=0.15

Cload out 0 50fF

Vdd vdd 0 1.8V
Vin in 0 1.8V

*simulation commands

.op

.dc Vin 0 1.8 0.01

.control
run
setplot dc1
display
.endc

.end
```

![terminal window noise margin](https://user-images.githubusercontent.com/89193562/132941122-635e2440-e1a6-4df2-9218-480b45ddf61d.JPG)

Figure 29. The snap shot of the terminal window for calculating the Noise Margins

![output window noise margin](https://user-images.githubusercontent.com/89193562/132941130-48c2c93d-3ad2-4a9c-acd1-c7caec2bf87c.JPG)

Figure 30. The snap shot of the output window for calculating the Noise Margins

- Method to calculate the Noise Margins from the plot:
     - Run the ngspice command and open the plot
     - left click on the point towards the top of the graph where the curvature seems to be '-1'
     - In this case it was `x0 = 0.766667, y0 = 1.71351`
     - Now, left click on the point towards the bottom of the graph where the curvature seems to be '-1'
     - In this case it was `x0 = 0.977333, y0 = 0.110811`. Let's consider these points as x1 and y1 thus making the coordinates `x1 = 0.977333, y1 = 0.110811`
     - For noise margin high we need Voh-Vih and in this case Voh=y0 and Vih=x1
     - For noise margin low we need Vil-Vol and in this case Vil=x0 and Vol=y1
     - Therefore, we get `NMh = 0.736177 and NMl = 0.655856`

# **Day 5: CMOS Power supply and device variation robustness evaluation**

## **Part 1: Static Behavior Evaluation - CMOS Inverter Robustness: Power Supply Variation**

### **_What was learnt:_**
- Whenever we move from 250nm nodes to lower nodes like 20nm or so on, we scale our supply voltage as well. For example, if things were working at 1V sometime back, now they will be operating at 0.7V

- A CMOS inverter can be operated at 0.5V as well and it has it's own advantages and disadvantages:
    - Advantages of using 0.5V supply:
        - There is a significant increase in gain (close to 50% improvement)
        - There is a significant reduction in energy consumption (close to 90% improvement)
    - Disadvantages of using 0.5V supply:
        - Performance impact (0.5V supply rising and falling edge is insufficient to completely charge or discharge the load capacitance)

### **_Lab Activity:_**

- To perform the lab activity for power supply scaling, we need the following code:

```
*Model Description
.param temp=27

*Including sky130 library files
.lib "sky130_fd_pr/models/sky130.lib.spice" tt

*Netlist Description

XM1 out in vdd vdd sky130_fd_pr__pfet_01v8 w=1 l=0.15
XM2 out in 0 0 sky130_fd_pr__nfet_01v8 w=0.36 l=0.15

Cload out 0 50fF

Vdd vdd 0 1.8V
Vin in 0 1.8V

.control

let powersupply = 1.8
alter Vdd = powersupply
        let voltagesupplyvariation = 0
        dowhile voltagesupplyvariation < 6
        dc Vin 0 1.8 0.01
        let powersupply = powersupply - 0.2
        alter Vdd = powersupply
        let voltagesupplyvariation = voltagesupplyvariation + 1
      end

plot dc1.out vs in dc2.out vs in dc3.out vs in dc4.out vs in dc5.out vs in dc6.out vs in xlabel "input voltage(V)" ylabel "output voltage(V)" title "Inveter dc characteristics as a function of supply voltage"

.endc

.end
```
![terminal window power supply variation](https://user-images.githubusercontent.com/89193562/132985847-4bd15226-3483-47e8-9961-1080e21564f8.JPG)

Figure 31. The snap shot of the terminal window to observe the power supply variation

![output window power supply variation](https://user-images.githubusercontent.com/89193562/132985866-6915c943-8cf2-4c48-a524-c4b4c1169147.JPG)

Figure 32. The snap shot of the output window to observe the power supply variation

- To calculate the gain for the given plot:
    - Select the curve for which the gain is to be calculated (In this case, we chose the plot for 1.8V Vdd)
    - Left click on the point where the slope of the curve is almost changing toward the top of the plot
    - The point obtained was `x0 = 0.766667, y0 = 1.71351`
    - Now, left click on the point where the slope of the curve is almost changing toward the bottom of the plot
    - The point obtained was `x0 = 0.982667, y0 = 0.1` but for our convenience let us consider the coordinates of the point to be x1, y1
    - Therefore, the point becomes `x1 = 0.982667, y1 = 0.1`
    - Subtract y1 from y0. So, `y0 - y1 = 1.61351`
    - Subtract x1 from x0. So, `x0 - x1 = -0.216`
    - Now, gain = (y0-y1)/(x0-x1)
    - Hence, `Gain(g) = |(1.61351)/(-0.216)| = |-7.46995| = 7.46995` 

## **Part 2: Static Behavior Evaluation - CMOS Inverter Robustness: Device Variation**

### **_What was learnt:_**
- There are two sources for device variation:
    - Etching Process Variation
    - Oxide Thickness
- Etching Process Variation:
    - The etching process will define the structures in the layout of the CMOS inverter.
    - Etching is a very important fabrication step
    - It is the process that defines the structure (width and the height)
    - Based on the structures that get defined by the process, it directly impacts the delay
- In layout of the CMOS inverter we have:
    - P-diffusion region which is indicated by green color.
    - Poly-silicon area which is indicated by red color.
    - Metal layer which is indicated by blue color.
    - N-diffusion region indicated by yellow color.
    - Contacts between two layers indicated by black crosses.
- Thickness of poly-silicon layer is the gate length annd it defiens at which node we are (20nm, 30nm, 45nm, etc.).
- Thickness of the P-diffusion layer is the width of the gate of the PMOS and the thickness of the N-diffusion layer is the width of the gate of the NMOS.
- Width identifies overlap area between the diffusion layer and the poly-silicon layer.

- Fabrication is basically a lab where we have a lot of things like chemicals, water, gases, etc. running and due to these the ideal structure is distorted.

![1631448142647](https://user-images.githubusercontent.com/89193562/132986827-95402e8e-0b25-40ef-b1fa-8122c6dcba7b.jpg)

Figure 33. The snap shot of the single inverter

![1631448142640](https://user-images.githubusercontent.com/89193562/132986894-f6d2a87b-acf9-4bd9-8b5d-a1f98e343a39.jpg)

Figure 34. The snap shot of the inverter chain

- Inverter Chain:
    - When inverters are connected back-to-back they are collectively called as "Inverter Chain".
    - In an inverter chain, the gates in the middle have same structures on both sides. So, it's very likely that this particular gate structure will have a repeated distortion because they are exposed to same kind of structures.
    - In an inverter chain, gates in the middle will have a structure which is different from the gates at the ends because they might be connected to different devices that will impact the gates
- Oxide Thickness:
    - In an ideal oxidation process, the gate oxide thickness will be constant throughout the process.
    - In real oxidation process, the gate oxide thickness will not be constant along the gate length.
    - In an inverter chain, the gate oxide thickness can vary for each transistor.
    - Oxide thickness directly affects the Id equation because Cox is dependant on it.

- Strong PMOS:
    - PMOS with less resistance (possibly least resistance if the size chosen is the greatest size possible)
    - PMOS is wider in size (possibly widest PMOS available)
- Weak NMOS:
    - NMOS with high resistance (possibly highest resistance if the size chosen is the least size possible)
    - NMOS is small in size (possibly smallest NMOS available)

- Strong NMOS:
    - NMOS with less resistance (possibly least resistance if the size chosen is the greatest size possible)
    - NMOS is wider in size (possibly widest NMOS available)
- Weak PMOS:
    - PMOS with high resistance (possibly highest resistance if the size chosen is the least size possible)
    - PMOS is small in size (possibly smallest PMOS available)

- With the variation from Weak PMOS - Strong NMOS to Strong PMOS - Weak NMOS, the switching threshold varies from roughly 0.7V to 1.4V which is fairly acceptable because behavior of the inverter is intact
- We can plot the variation if we move from Weak PMOS - Strong NMOS to Strong PMOS - Weak NMOS using SPICE simulation and the plot is given below:


- From the plot given above, we can make the following conclusions:
    - Variation in Noise Margin high (NMh) is roughly from 2.5V to 2.1V which is a variation of 400mV which is good enough to filter out high voltage variations
    - Variation in Noise Margin low (NMl) is roughly from 0V to 0.3V which is a variation of 300mV which is good enough to filter out low voltage variations
    - Overall, variation in the Noise margins is low and this leaves the operation of the gate intact.

### **_Lab Activity:_**

- To perform the lab activity for device variation, we need the following code:

```
*Model Description
.param temp=27

*Including sky130 library files
.lib "sky130_fd_pr/models/sky130.lib.spice" tt

*Netlist Description

XM1 out in vdd vdd sky130_fd_pr__pfet_01v8 w=7 l=0.15
XM2 out in 0 0 sky130_fd_pr__nfet_01v8 w=0.42 l=0.15

Cload out 0 50fF

Vdd vdd 0 1.8V
Vin in 0 1.8V

*simulation commands

.op

.dc Vin 0 1.8 0.01

.control
run
setplot dc1
display
.endc

.end
```

![terminal window device variation](https://user-images.githubusercontent.com/89193562/132985962-a05f4559-ce5d-4af5-bf2e-67e091c577dd.JPG)

Figure 35. The snap shot of terminal window to observe device variation

![output window device variation](https://user-images.githubusercontent.com/89193562/132985983-6313769f-5ef4-432d-87c9-ef39f7e572f0.JPG)

Figure 36. The snap shot of output window to observe device variation

- Since the pfet width is very huge as compared to the nfet width, the plot is shifted towards right
- To find the value of the switching threshold:
    - Zoom in on the plot where Vin ~ Vout by right clicking and dragging the cursor to select the area
    - Zoom until the value of switching threshold becomes almost certain
    - Left click on the point where Vin is roughly equal to Vout
    - A point `x0 = 0.988209, y0 = 0.988191` is obtained
    - Since x0 ~ y0. Therefore, Switching Threshold Voltage = Vm = x0 = y0 = 0.988V

# Conclusion

# References

- [https://github.com/kunalg123/sky130CircuitDesignWorkshop](https://github.com/kunalg123/sky130CircuitDesignWorkshop)
- [https://www.vsdiat.com/](https://www.vsdiat.com/)
