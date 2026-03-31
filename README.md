# DIRECTIONAL COUPLER EXPERIMENT

**Aim:**
To study the characteristics of a directional coupler and to measure:

* Coupling factor
* Insertion loss
* Directivity

**THEORY:**
A Directional Coupler is a passive microwave component used to sample or divide the input signal in a predetermined direction. It is a four-port network in which power entering one port is distributed among the remaining ports in a controlled manner.

The four ports of a directional coupler are:

Port 1 – Input port
Port 2 – Through port
Port 3 – Coupled port
Port 4 – Isolated port

When microwave power is applied at Port 1, the major portion of the power is delivered to the through port (Port 2). A small fraction of the input power is coupled to the coupled port (Port 3), while ideally no power appears at the isolated port (Port 4). This property makes the device directional.
Principle of Operation

The operation of a directional coupler is based on the principle of electromagnetic field coupling between adjacent transmission lines or waveguides. Due to this coupling, a portion of the travelling wave energy is transferred from the main line to the auxiliary line.

The coupling depends on:

Distance between transmission lines
Length of coupling region
Operating frequency
Characteristics of Directional Coupler

The performance of a directional coupler is defined using the following parameters:

1. Coupling Factor (C)

It is the ratio of input power to the power available at the coupled port.

2. Insertion Loss (IL)

It represents the loss of power between input port and through port.

3. Directivity (D)

It indicates the ability of the coupler to distinguish between forward and backward travelling waves.

4. Isolation (I)

It is the measure of power leakage to the isolated port.

**PROCEDURE:**

**A.ANTENNA RADIATION PATTERN:**
Connections Setup
Connect the microwave bench components as per the block diagram:
Microwave source → Isolator → Directional Coupler → Detector/Power meter.
Switch ON the Equipment
Switch ON the microwave source and allow it to warm up for a few minutes to obtain stable output.
Set Operating Frequency
Adjust the frequency of the microwave source to the required value.
Input Power Measurement
Measure the input power by connecting the detector to the input port (Port 1) and note the reading.
Through Power Measurement
Connect the detector to the through port (Port 2) and record the output power.
Coupled Power Measurement
Connect the detector to the coupled port (Port 3) and measure the coupled power.
Isolated Power Measurement
Connect the detector to the isolated port (Port 4) and note the isolated power.
Repeat Readings
Repeat the above measurements for different input power levels or frequencies if required.
Calculations
Using the observed readings, calculate:
Coupling Factor
Insertion Loss
Directivity
Isolation
Tabulation
Enter all observed values in a tabular column for analysis.

**GAIN MEASUREMENT:**

1.	Set up the equipments as shown in figure both horns should be in line.
2.	Keep the range dB switch meter at 50DB position with gain control full.
3.	energize the Gunn oscillator for maximum output at desired frequency with modulating amplitude and frequency of Gunn power supply and by tuning of detector.
4.	obtain full scale deflection in VSWR meter with variable attenuator.
5.	replace the transmitting horn by detector mount and change the appropriate range dB positon to get the deflection.on scale(do not touch the gain control knob).note and record the range dB position and deflection of VSWR meter.
6.	calculate the difference in dB between the power measured in step 4 and 5.

**EXAMPLE**

Suppose that a deflection of 5DB on 20DB range dB position was obtained in step 5,the difference between 4 and 5 is
50-(20-5)=25DB 
Convert the dB in to power ratio.as for above example is will come 316 which will be pt/pr .Calculate gain by following equation:
G= 4ΠS/	√ Λ 0 *	√Pr / Pt
In our above example suppose operating frequency is 9GHZ λ0=3.33CM.where c is velocityof light and is 3*1010CM/sec and distance between antennas is 150CM(suppose).

7.	convert g into dB in above exampleG dB =10LOG318=15.02DB
8.	the same setup can be used for other frequency of operation.

**BLOCK DIAGRAM:**

<img width="600" height="375" alt="image" src="https://github.com/user-attachments/assets/2c0bbf02-331b-448f-89d9-acea4f3986af" />


**TABULATION:** 

| S.No | P1 Input (mW) | P2 Through (mW) | P3 Coupled (mW) | P4 Isolated (mW) | Coupling (dB) | Insertion Loss (dB) | Directivity (dB) | Isolation (dB) |
|------|--------------|----------------|----------------|-----------------|---------------|---------------------|------------------|----------------|
| 1    | 10           | 8              | 1              | 0.1             | 10            | 0.97                | 10               | 20             |
| 2    | 12           | 9              | 1.2            | 0.12            | 10            | 1.25                | 10               | 20             |
| 3    | 15           | 12             | 1.5            | 0.15            | 10            | 0.97                | 10               | 20             |
| 4    | 20           | 16             | 2              | 0.2             | 10            | 0.97                | 10               | 20             |


**RESULT:**

The characteristics of the directional coupler were studied and the following values were obtained:

* Coupling Factor (C) ≈ 10 dB
* Insertion Loss (IL) ≈ 0.97 dB to 1.25 dB
* Directivity (D) ≈ 10 dB
* Isolation (I) ≈ 20 dB


