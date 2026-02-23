# Inverting-Amplifier-using-Proteus
## Experiment 1
Design and Simulation of Inverting Amplifier using Op-Amp (μA741) in Proteus
## Aim
To design and simulate an Inverting Amplifier using μA741 Op-Amp in Proteus Design Suite and verify the voltage gain experimentally.
## Apparatus / Components Required
<img width="485" height="190" alt="image" src="https://github.com/user-attachments/assets/7aebc8c3-b7bd-4579-8640-c9c8c08e0aa5" />



## Theory
An Inverting Amplifier is a closed-loop amplifier configuration where the input signal is applied to the inverting terminal (-) of the op-amp through resistor R1, and feedback resistor Rf is connected between output and inverting terminal.
The non-inverting terminal (+) is grounded.

## Circuit Description
•	Pin 2 → Inverting input<br/>
•	Pin 3 → Non-inverting input (Grounded)<br/>
•	Pin 6 → Output<br/>
•	Pin 7 → +15V<br/>
•	Pin 4 → -15V<br/>
The input sine wave is applied through R1 and output is taken from pin 6.
## Circuit Diagram
<img width="1920" height="1200" alt="Screenshot 2026-01-23 094619" src="https://github.com/user-attachments/assets/4a3d0163-3acc-4800-a4dc-e84b91691de7" />

## Tabulation
<img width="644" height="144" alt="image" src="https://github.com/user-attachments/assets/b36f28ed-0fe6-4dea-9a5f-abcb3d4fbb5b" />

## Simulation Procedure (Proteus)
1.	Open Proteus Design Suite
2.	Select components:
o	μA741
o	Resistors
o	AC Signal Generator
o	Oscilloscope
3.	Connect circuit as per inverting amplifier configuration.
4.	Set:
o	R1 = 10kΩ
o	Rf = 100kΩ
o	Input = 1V, 1kHz sine wave
5.	Apply ±15V power supply.
6.	Run simulation.
7.	Observe input and output waveforms on CRO.
##  Waveform Observation
•	Input: Sine wave<br/>
•	Output: Amplified sine wave<br/>
•	Phase Shift: 180°<br/>
•	Gain ≈ -10<br/>

<img width="1920" height="1200" alt="Screenshot 2026-01-23 094534" src="https://github.com/user-attachments/assets/2be7f2be-b51a-4dee-b152-f84167fb938a" />

## Result
The Inverting Amplifier using μA741 Op-Amp was successfully designed and simulated in Proteus.
The practical output voltage closely matches the theoretical value.
The gain obtained is approximately -10, and the output waveform is inverted with respect to the input waveform.

