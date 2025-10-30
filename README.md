# FM-using-Python

Aim


To implement and analyze frequency modulation (FM) using Python's NumPy and Matplotlib libraries. 

Apparatus Required

1.	Software: Python with NumPy and Matplotlib libraries
2.	Hardware: Personal Computer
  
Theory

Frequency Modulation (FM) is a method of transmitting information over a carrier wave by varying its frequency in accordance with the amplitude of the input signal (message signal). The frequency of the carrier wave is varied according to the instantaneous amplitude of the message signal. The general form of an FM signal is:



Algorithm


1.	Initialize Parameters: Set the values for carrier frequency, message frequency, sampling frequency, and frequency deviation.
2.	Generate Time Axis: Create a time vector for the signal duration.
3.	Generate Message Signal: Define the message signal as a cosine wave.
4.	Compute the Integral of the Message Signal: Calculate the integral of the message signal over time.
5.	Generate FM Signal: Apply the FM modulation formula to obtain the modulated signal.
6.	Plot the Signals: Use Matplotlib to plot the message signal, carrier signal, and modulated signal.

Program

<img width="516" height="491" alt="Screenshot 2025-10-23 200027" src="https://github.com/user-attachments/assets/8875e297-4f38-4793-8074-663733507057" />


Output Waveform

<img width="794" height="609" alt="Screenshot 2025-10-23 200044" src="https://github.com/user-attachments/assets/39095612-7e6c-444f-85d5-9c6e92a1c361" />


Tabular Column

![WhatsApp Image 2025-10-30 at 14 31 41_d751b781](https://github.com/user-attachments/assets/40fd1a84-1cf2-441d-9ae3-0b1f08605846)



Calculation

<img width="1260" height="579" alt="image" src="https://github.com/user-attachments/assets/fdd49c65-e713-4e71-9501-37cbd2e5dc09" />



Result


The message signal, carrier signal, and frequency modulated (FM) signal will be displayed in separate plots. The modulated signal will show frequency variations corresponding to the amplitude of the message signal.
