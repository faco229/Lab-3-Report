# Lab-3-Report
# Lab Report Title: Lab 3—Transistors as Switches

**Authors:** Faith Cox & Quinn Rison  
**Date:** 2/17/2025  

## Introduction

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

Before proceeding, all resistors and capacitors should be measured using a DMM.

### Circuit 1
**Figure 1: Circuit 1 – A resistor, LED, and switch in series with five volts supplied.**  

Ensure the voltage output is between 4.99V and 5.01V. Measure voltage at test points T1, T2, T3, and T4.

**Figure 2: Testing Locations for Circuit 1**  

## Results
### Part 1: LED Driving Circuits
#### Table 1: Real Values of Resistors
| Resistor (Nominal) | Actual Value (Ω) |
|--------------------|-----------------|
| 270Ω             | 269.4Ω          |
| 1kΩ              | 0.982kΩ         |
| 2.2Ω             | 2.4Ω            |

#### Table 2: Measurements in a Circuit with an LED directly connected to a switch
| Test Point | Voltage (Switch On) | Voltage (Switch Off) |
|-----------|-------------------|-------------------|
| T2        | 1.923V            | 5.01V            |
| T3        | 0.001V            | 3.69V            |

| Component | Voltage Across (Switch On) | Voltage Across (Switch Off) |
|-----------|-------------------------|-------------------------|
| R1        | 3.08V                   | 0V                      |
| LED1      | 1.918V                   | 0.038V                  |
| S1        | 0V                        | 0V                      |

| Current Through | Switch On | Switch Off |
|----------------|-----------|------------|
| LED1          | 11.33mA   | 0.02mA     |

#### Table 3: Measurements on a circuit with an LED connected through a transistor
| Test Point | Voltage (Switch On) | Voltage (Switch Off) |
|-----------|-------------------|-------------------|
| T2        | 1.94V             | 4.998V           |
| T3 (VCE)  | 0.022V            | 3.68V            |
| T5 (VBE)  | 0.695V            | 0.005V           |
| T6        | 5.0V              | 0.001V           |

#### Table 4: LED Brightness Characteristics
**Figure 3: LED Brightness Characteristics Graph**  

### Part 2: Motor Driving Circuit
#### Table 5: Controlling Motor Current and Speed using a Transistor
| Test Point | Slow Motor | Midpoint 1 | Midpoint 2 | Fast Motor |
|------------|------------|-----------|-----------|-----------|
| T2        | 4.85V     | 4.79V     | 4.78V     | 4.76V     |
| T3 (VCE)  | 3.42V     | 0.46V     | 0.77V     | 0.1V      |
| T5 (VBE)  | 0.65V     | 0.68V     | 0.69V     | 0.71V     |
| T6        | 1.05V     | 1.40V     | 1.31V     | 4.96V     |

#### Table 6: Transistor Characteristics Table
**Figure 4: Transistor Characteristics Graph**  

## Discussion
### Discussion Question 1: How does the current through the LED compare between circuits 1 and 2?
- T2 (Collector Voltage): **VC = 4.76V**
- T3 (Emitter Voltage): **VE = 4.66V**

\[V_{CE} = V_C - V_E\]  
\[V_{CE} = 4.76V - 4.66V = 0.1V\]  

- **Measured VCE in LED Circuit:** 0.022V
- **Measured VCE in Motor Circuit:** 0.1V

The motor circuit has a higher VCE due to its greater current demand.

### Discussion Question 2: Comparison with Datasheet VCE
- **Voltage across R1 (Fast Setting):** VR1 = 0.210V
- **R1 = 2.2Ω**

\[I = \frac{V}{R}\]  
\[I_{Motor} = \frac{0.210V}{2.2Ω} = 91.5mA\]

- **Current through LED circuit:** 18.3mA
- **Current through Motor Circuit:** 91.5mA

Motors draw significantly more current than LEDs. The transistor allows for higher current flow necessary for the motor.

## Conclusion
Summary of findings and key takeaways.
