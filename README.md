## Experiment No: 4
INTEGRATOR USING OP-AMP (μA741)
## Aim
To design and simulate an Integrator circuit using μA741 in Proteus Design Suite and verify that the output is proportional to the integral of the input voltage.
## Apparatus Required
•	μA741 Op-Amp
•	Resistor R = 10 kΩ
•	Capacitor Cf = 0.01 µF
•	Signal Generator
•	Dual Power Supply (±15V)
•	CRO / Oscilloscope
•	Connecting wires
## Circuit Diagram
<img width="1309" height="581" alt="Screenshot 2026-02-23 094200" src="https://github.com/user-attachments/assets/e6c8affd-f880-47ab-b8b9-73adce2ed3af" />

## Connection Details:
•	Input signal → Resistor (R) → Inverting terminal (Pin 2)
•	Feedback capacitor (Cf) → Between Output (Pin 6) and Pin 2
•	Non-inverting terminal (Pin 3) → Ground
•	Pin 7 → +15V
•	Pin 4 → −15V
## Theory
An Integrator circuit produces an output voltage proportional to the integral of the input voltage.
## Working Principle:
•	When input is constant → output is ramp signal
•	Output is inverted
•	Output depends on time
For Sine Wave Input:
•	Output lags input by 90°
•	Output amplitude decreases with frequency
## Procedure
1.	Open Proteus software.
2.	Select μA741, resistor, capacitor, signal generator, and CRO.
3.	Connect circuit in integrator configuration.
4.	Apply ±15V power supply.
5.	Set input waveform (1V, 1kHz).
6.	Run simulation.
7.	Observe input and output waveforms on CRO.
## Tabulation
<img width="751" height="290" alt="Screenshot 2026-02-23 094226" src="https://github.com/user-attachments/assets/2d8d391c-b9c8-449b-af0e-8f1236c2ca22" />

S.No	           Input Signal	 Frequency	      Expected Output	               Practical Observation
## Waveforms
<img width="1612" height="1030" alt="Screenshot 2026-02-23 094242" src="https://github.com/user-attachments/assets/773a122c-4d3f-4307-b239-0abd67255448" />

## Result
The Integrator circuit using μA741 Op-Amp was successfully designed and simulated in Proteus.
The output waveform is proportional to the integral of the input signal.
The circuit behaves as an integrator.
## Conclusion
•	Output lags input by 90° (for sine input).
•	Output amplitude decreases with increase in frequency.
•	Used in waveform generation and analog computation.
## Viva Questions
1.	What is an integrator circuit?
   A circuit that produces output proportional to the integral of input voltage.
2.	Write the output equation of integrator.
   Vout​=−RC1​∫Vin​dt
3.	Why does output lag input?
   Because integration of sine gives negative cosine, which lags by 90°.
4.	What happens at very low frequency?
   Output amplitude becomes very large and may saturate.
5.	What is practical integrator?
    An integrator with an additional resistor in parallel with the capacitor to prevent saturation and improve stability.
