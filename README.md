# Lab-3-Report
# Lab Report Title: Lab 3—Transistors as Switches

**Authors:** Faith Cox & Quinn Rison  
**Date:** 2/17/2025  

## Introduction
The objective of this lab was to investigate how transistors operate as switches and their application in managing circuits. Through assembling different circuit setups, we looked into voltage variations, current behavior, and transistor properties in contexts such as LED and motor control. The tasks included constructing several circuits, recording voltage and current measurements, and assessing transistor behavior in various conditions. This exercise offered significant understanding of the way transistors modulate current and voltage, serving effectively as electronic switches.

## Methods/Tests
To repeat this experiment, a few components will be needed:
- Digital Multimeter (DMM)
- DC power supply
- Resistors: 2.2Ω, 270Ω, 1000Ω
- LED
- Sliding switch
- Electric motor
- NTE 125 diode
- 1000Ω trimmer potentiometer
- TIP31C transistor

To repeat this experiment, a few components will be needed. These components are a digital multimeter (DMM), DC power supply, 2.2-ohm, 270-ohm, and 1000-ohm resistor. More components such as any type of LED, a sliding switch, an electric motor, a NTE 125 diode, a 1000-ohm trimmer potentiometer, and a TIP31C transistor. 

Before going any further in the experiment, all resistors and capacitors should be measured with the DMM. To measure the resistance, have the DMM set to measure the resistance and connect the nodes to the ends of each resistor and record the values to compare to what they should be theoretically. The DMM should read in ohms (). Do the same for the capacitors, however, make sure the DMM is set to read capacitance the units should be in farads ().

The first task in this experiment involves building a small circuit with the 270-ohm resistor, and LED, and a switch. Before building the circuit, record the resistor values of the resistor(s) being used in that specific circuit. The first circuit should look as follows:

### Circuit 1

<p align="center">
  <img src="https://github.com/faco229/Lab-3-Report/blob/main/Fig1-Circuit%201.jpg" width="100">
  <br>
  <b>Figure 1:</b> Circuit 1 - A resistor, LED, and Switch in series with five volts supplied.
</p>


Before proceeding, all resistors and capacitors should be measured using a DMM. For these measurements, see Table 1.

Measure voltage at test points T1, T2, T3, and T4. Once the circuit is built, make sure that the DC power supply is set for five volts and measure the voltage output with the DMM. Make sure that the output on the DMM is no more or no less than 5.01 or 4.99 volts. 
Now that the voltage is secure, and the circuit is built we can begin measuring our voltages at each of the testing points. These are labeled T1, T2, T3, and T4. Be aware when measuring the voltage at each of these testing points with the DMM it should be with respect to ground, in this case, T4. Therefore, the black node of the DMM should be placed here when measuring throughout the experiment. If the red node of the DMM were placed here, a negative reading would show, that is why the black node is preferred in this scenario. Here are the testing locations:
<p align="center">
  <img src="https://github.com/faco229/Lab-3-Report/blob/main/Fig2-testing%20for%20circuit%201.jpg" width="120">
  <br>
  <b>Figure 2:</b> Testing Locations for Circuit 1.
</p>
It can be expected that T1 measures five volts but could deviate some due to small voltage drops. Now, measure the voltage at T2 and T3 with the switch on and the switch off and record the results on the table. Next, measure the voltage drop across R1, the LED, and the switch with the switch on and the switch off and record these results in a table. Last, the current through the LED needs to be measured. To do so, switch the red lead of the DMM and make sure it is set to read current. Another important note is that to be able to measure current, the circuit needs to be broken at one point to attach the nodes to that way the circuit remains in series. Record the measured current through the LED with the switch on and switch off and record the results in a table. 

The next circuit that will be built is a bit bigger and should look as follows:
<p align="center">
  <img src="https://github.com/faco229/Lab-3-Report/blob/main/Fig3.jpg" width="500">
  <br>
  <b>Figure 3:</b> Circuit 2 – Two voltage supplies, potentiometer, 1000-ohm and 270-ohm resistor, and LED.
</p>

<p align="center">
  <img src="https://github.com/faco229/Lab-3-Report/blob/main/Image1-LED%20at%20full%20brightness.jpg" width="500">
  <br>
  <b>Image 1:</b> Completed LED circuit - LED at full brightness.
</p>

As always, before building the circuit ensure that resistor values are measured with the DMM and recorded on a table to be used later for analysis. Here in this circuit at T7 the 5V DC output needs to be connected and at T1 the main output should be connected. With a similar process to the first circuit, the voltages will be measured across each element with respect to ground, again in this case T4. With the DMM set to read in volts, and the black node of the DMM set on T4, begin measuring the voltage drops at T2, T3, T5, and T6 with the switch on and the switch off. Record the results. After measuring the different testing locations, now measure the voltage drop across R1, the LED, R2, and S1, with the switch on and with the switch off and record the results. After all the voltages have been recorded, switch the lead in the DMM to measure current and have the DMM set to read current. Disconnect part of the circuit to measure the current at the LED and R2 with the switch on and the switch off. Record these current measurements in a table. 
The next circuit that will be built involves controlling the amount of light produced by the LED with the transistor. Like the last circuits, the voltage across different testing locations and elements of the circuit will be measured. However, this circuit does not involve a switch. Therefore, instead of comparing the values of the voltage with the switch on or off, the values that are recorded at different LED light levels will be compared. For instance, there will be a dim mode, essentially the lowest amount of light the LED can produce, two midway points, and lastly the brightest the LED can show. Here is what the circuit should look like:

<p align="center">
  <img src="https://github.com/faco229/Lab-3-Report/blob/main/Image%204.jpg" width="500">
  <br>
  <b>Figure 4:</b> Circuit 3 - two resistors, a potentiometer, an LED, and a transistor.
</p>

Again, the idea is that with the transistor it can control the amount of current getting through to the LED will ultimately affect the amount of light that the LED produces. When starting to take measurements, get the LED to show as dimly as possible. Utilizing the potentiometer for this part of the experiment, the voltage at T6 is what will be recorded. Take the dim measurement at the voltage level where the light is barely visible and take the bright measurement at the lowest voltage amount that is producing the most amount of light. The two midway points mentioned earlier will lie between the dim and bright voltage measurements. With the LED producing a dim light, measure the voltage drop at T2, T3, T5, T6, R1, the LED, and R2. Record the results in a table. Repeat this process at two midway points and record the results. Lastly, repeat this process again when the LED is shining the brightest. Record the voltage drop across each of the elements. Similarly to the other circuits constructed thus far, the current needs to be measured at each of the light settings. To measure the current, make sure the leads of the DMM are in the correct position and that the DMM is set to read amps. Once these steps have been ensured, an element in the circuit will have to be broken to have the nodes of the DMM in series with the circuit. Once all these steps are completed there will be a current reading. Record the results on a table and repeat this process for both midpoints and the bright setting of the LED. 
Now, the last circuit is to be built. It should look as follows:

<p align="center">
  <img src="https://github.com/faco229/Lab-3-Report/blob/main/Fig%205.jpg" width="500">
  <br>
  <b>Figure 5:</b> Circuit 4 -Diode, motor, and transistor.
</p>


## Results
### Part 1: LED Driving Circuits
#### Table 1: Real Values of Resistors
| Resistor (Nominal) | Actual Value (Ω) |
|--------------------|-----------------|
| 270Ω             | 269.4Ω          |
| 1kΩ              | 0.982kΩ         |
| 2.2Ω             | 2.4Ω            |



The following data was collected based on the circuit configuration in Figure 2:
#### Table 2: Measurements in a Circuit with an LED directly connected to a switch
| Test Point | Voltage (Switch On) | Voltage (Switch Off) |
|-----------|-------------------|-------------------|
| T2        | 1.923V            | 5.01V            |
| T3        | 0.001V            | 3.69V            |
|---------|----------------------------|-----------------------------|
| Component | Voltage Across (Switch On) | Voltage Across (Switch Off) |
| R1        | 3.08V                   | 0V                      |
| LED1      | 1.918V                   | 0.038V                  |
| S1        | 0V                        | 0V                      |
|----------------|-----------|------------|
| Current Through | Switch On | Switch Off |
| LED1          | 11.33mA   | 0.02mA     |


The data in the following table (Table 3), is from the circuit shown in Figure 3:
#### Table 3: Measurements on a circuit with an LED connected through a transistor
| Test Point | Voltage (Switch On) | Voltage (Switch Off) |
|-----------|-------------------|-------------------|
| T2        | 1.94V             | 4.998V           |
| T3 (VCE)  | 0.022V            | 3.68V            |
| T5 (VBE)  | 0.695V            | 0.005V           |
| T6        | 5.0V              | 0.001V           |

After using the potentiometer to change the voltage, the following tables and graphs were created to display the results of our findings:
<p align="center">
  <img src="https://github.com/faco229/Lab-3-Report/blob/main/LED%20Brightness%20Characteristics%20Chart.jpg" width="500">
  <br>
  <b>Table 4:</b> LED Brightness Characteristics Table
</p>


<p align="center">
  <img src="https://github.com/faco229/Lab-3-Report/blob/main/LED%20Brightness%20Characteristics%20Graph.jpg" width="600">
  <br>
  <b>Figure 6:</b> LED Brightness Characteristics Graph
</p>


### Part 2: Motor Driving Circuit

<p align="center">
  <img src="https://github.com/faco229/Lab-3-Report/blob/main/Table5.jpg" width="600">
  <br>
  <b>Table 5:</b> Controlling Motor Current and Speed using a Transistor
</p>


<p align="center">
  <img src="https://github.com/faco229/Lab-3-Report/blob/main/Transistor%20Characteristics%20Table.jpg" width="600">
  <br>
  <b>Table 6:</b> Transistor Characteristics Table
</p>

<p align="center">
  <img src="https://github.com/faco229/Lab-3-Report/blob/main/Transistor%20Characteristics%20Graph.jpg" width="600">
  <br>
  <b>Figure 7:</b> Transistor Characteristics Graph
</p>

<p align="center">
  <img src="https://github.com/faco229/Lab-3-Report/blob/main/BJT%20Lecture.jpg" width="600">
  <br>
  <b>Image 2:</b> Lecture on BJT (Bipolar Junction Transistor)-Semiconductor acting as an amplifier.
</p>


<p align="center">
  <img src="https://github.com/faco229/Lab-3-Report/blob/main/Motor%20attached%20to%20circuit%20at%20fast%20speed.jpg" width="500">
  <br>
  <b>Image 3:</b> Circuit used for esting various motor speeds.
</p>


## Discussion
Graph interpretation:
In Figure 7: Transistor Characteristics Graph, the current collector (IC) is fairly consistent with the other categories, but the IB is much higher compared to the other settings. The following equation is needed to find gain (β): 
<p align="center">
  <img src="https://github.com/faco229/Lab-3-Report/blob/main/Calc_Gain.jpg" width="100">
  <br>
  <b>Equation 1:</b> Circuit used for esting various motor speeds.
</p>

Even though the collector current remains stable, the increased IB reduces the ratio, which lowers the gain. In addition, motors consume a lot of current, especially compared to the small, dimmable LED light. This means the first time we really saw current was when the motor was at full speed. 

### Discussion Question 1: How does the current through the LED compare between circuits 1 and 2?
- T2 (Collector Voltage): **VC = 4.76V**
- T3 (Emitter Voltage): **VE = 4.66V**

<p align="center">
  <img src="https://github.com/faco229/Lab-3-Report/blob/main/Calc_discussion1.jpg" width="400">
  <br>
  <b>Equation 2:</b> Transistor Characteristics Graph
</p>


- **Measured VCE in LED Circuit:** 0.022V
- **Measured VCE in Motor Circuit:** 0.1V

The motor circuit has a higher VCE due to its greater current demand.

### Discussion Question 2: Comparison with Datasheet VCE
The datasheet mentions a maximum voltage drop (VCE) of 1.2V at saturation. We would like a much smaller value, such as the fraction of a volt that you measured in the first circuit across the switch, S1, when it is on. How does your measured VCE compare to the one listed in the datasheet? Do you think we are operating this transistor in the saturation region?

- **Voltage across R1 (Fast Setting):** VR1 = 0.210V
- **R1 = 2.2Ω**

<p align="center">
  <img src="https://github.com/faco229/Lab-3-Report/blob/main/Calc_discussion2.jpg" width="400">
  <br>
  <b>Equation 3:</b> Transistor Characteristics Graph
</p>


- **Current through LED circuit:** 18.3mA
- **Current through Motor Circuit:** 91.5mA

The motor draws roughly five times more current than the LED circuit configuration.
Meeting the current needs of the LED with the switch proved to be challenging in this lab (needed 18.3mA), so it would not be able to support the motor directly (needing 91.5mA). The transistor is needed since it amplifies the IB to allow for higher current flow through the motor.


## Conclusion
The goal of this lab was to explore the functionality and the importance of transistors as switches and their role in controlling circuits. By building various circuit configurations, we examined voltage drops, current flow, and transistor characteristics in LED and motor control applications. The work involved building multiple circuits, measuring voltages and currents, and analyzing transistor performance in different configurations. We observed how transistors amplify small currents to control larger loads, making them essential for driving higher-power components such as motors. Through our findings, we confirmed that transistors effectively regulate voltage and current, improving circuit efficiency. Our measurements indicated that transistors in saturation mode provide minimal voltage drop, allowing for efficient switching. Additionally, we found that motors require significantly more current than LEDs, necessitating the use of a transistor to handle the higher current demand. The outcome provided valuable insights into how transistors regulate current and voltage, effectively acting as electronic switches. This lab reinforced the practical importance of transistors in circuit design and highlighted the need for precise voltage and current measurements to optimize performance.
