# FM

# EXP NO: 4	GENERATION AND DETECTION OF FM


# AIM:
To write a program for Frequency Modulation and Demodulation using SCILAB and to observe and measure the frequency deviation and the modulation index of FM.


# EQUIPMENTS REQUIRED

•	Computer with i3 Processor
•	SCI LAB


# THEORY:

Frequency modulation is a type of modulation in which the frequency of the high frequency (carrier) is varied in accordance with the instantaneous value of the modulating signal.
FREQUENCY DEVIATION f and MODULATION INDEX m f :
The frequency deviation f represents the maximum shift between the  modulatedsignal
frequency, over and under the frequency of the carrier.

We define modulation index m f the ratio between f and the modulating frequency
m= f / fm


# FREQUENCY MODULATION GENERATION:
The circuits used to generate a frequency modulation must vary the frequency of a high frequency signal (carrier) as function of the amplitude of a low frequency signal (modulating signal). In practice there are two main methods used to generate FM.

# Algorithm
1.	Define Parameters:
•	Fs: Sampling frequency.
•	T: Duration of the signal.
•	Fc: Carrier frequency.
•	Fm: Frequency of the modulating signal.
•	Beta: Modulation index, which controls the extent of frequency deviation.
2.	Generate Signals:
•	Modulating signal: Sinusoidal signal used for modulation.
•	Carrier signal: The high-frequency carrier signal.
•	Modulated signal: FM modulated signal calculated by varying the carrier frequency according to the modulating signal.
3.	FM Modulation:
•	Modulated signal is obtained by modulating the carrier signal with the modulating signal.
 
4.	FM Demodulation:
•	Differentiation: Computes the derivative of the modulated signal to extract frequency variations.
•	Envelope Detection: Takes the absolute value to retrieve the envelope of the signal.
•	Low-pass Filtering: Applies a Butterworth low-pass filter to smooth the envelope and recover the original modulating signal.
5.	Visualization:
•	Plots the modulating signal, carrier signal, FM modulated signal, and demodulated signal for analysis.



# PROCEDURE


•	Refer Algorithms and write code for the experiment.
•	Open SCILAB in System
•	Type your code in New Editor
•	Save the file
•	Execute the code
•	If any Error, correct it in code and execute again
Verify the generated waveform using Tabulation and Model Waveform

# MODEL GRAPH:

<img width="512" height="365" alt="image" src="https://github.com/user-attachments/assets/acd787bd-5281-4f1b-802f-1aa39fac9189" />


# Program

<img width="1600" height="1001" alt="WhatsApp Image 2026-05-28 at 21 40 01" src="https://github.com/user-attachments/assets/b7da344a-aaa8-42ac-bfec-39838166f71e" />

# Output Waveform

<img width="1600" height="999" alt="WhatsApp Image 2026-05-28 at 21 40 13" src="https://github.com/user-attachments/assets/0c27f4aa-9ae0-4b9f-a1b0-cc2c7fc19143" />


# Tabulation

<img width="1280" height="706" alt="image" src="https://github.com/user-attachments/assets/a0e18572-ad06-4e25-b1d8-261eb28ca087" />


# Calculation

<img width="1024" height="1280" alt="image" src="https://github.com/user-attachments/assets/a69039a5-7114-4c6d-91b6-9fc9c2a8673b" />

# RESULT:

Thus, the frequency modulation and demodulation is successfully done and the output is experimentally verified.


