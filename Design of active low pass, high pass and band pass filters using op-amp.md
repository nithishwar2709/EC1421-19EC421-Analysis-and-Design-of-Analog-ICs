# EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
# DESIGN OF ACTIVE LOW PASS,HIGH PASS AND BAND PASS FILTERS USING OP-AMP 

## AIM: 

To design and obtain the frequency response of 
i) First order Low Pass Filter (LPF) 
ii) First order High Pass Filter (HPF) 
iii) Band pass filter
 
## APPARATUS REQUIRED

<img width="625" height="170" alt="image" src="https://github.com/user-attachments/assets/900fc8b3-3a8c-4208-bf52-98cc9e281e21" />

## THEORY
## LOW PASS FILTER 
 A LPF allows frequencies from 0 to higher cut of frequency, fH.  At fH the gain is 0.707 
Amax, and after fH gain decreases at a constant rate with an increase in frequency.  The gain 
decreases 20dB each time the frequency is increased by 10.  Hence the rate at which the gain 
rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in 
frequency.  The frequency f=fH is called the cut off frequency because the gain of the filter at this 
frequency is down by 3 dB from 0 Hz.  Other equivalent terms for cut-off frequency are -3dB 
frequency, break frequency, or corner frequency.
# HIGH PASS FILTER 
The frequency at which the magnitude of the gain is 0.707 times the maximum value of 
gain is called low cut off frequency.  Obviously, all frequencies higher than fL are pass band 
frequencies with the highest frequency determined by the closed –loop band width all of the op
amp. 
# BAND PASS FILTER 
A band pass filter has a pass band between two cutoff frequencies fH and fL such that fH > 
fL.  Any input frequency outside this pass band is attenuated.  There are two types of band-pass 
filters.  Wide band pass and Narrow band pass filters.  We can define a filter as wide band pass if 
its quality factor Q <10.  If Q>10, then we call the filter a narrow band pass filter.  A wide band 
pass filter can be formed by simply cascading high-pass and low-pass sections.  The order of 
band pass filter depends on the order of high pass and low pass sections.

## CIRCUIT DIAGRAM: 
## LOW_PASS

![WhatsApp Image 2025-11-19 at 10 34 10_81aa1c24](https://github.com/user-attachments/assets/068c6d74-9362-47d8-91cf-db140f59b676)

## HIGH-PASS

![WhatsApp Image 2025-11-19 at 10 34 11_803111bf](https://github.com/user-attachments/assets/8680023c-552e-454e-ac03-f884861a0ba5)

## BAND-PASS

![WhatsApp Image 2025-11-19 at 10 34 13_2c38b172](https://github.com/user-attachments/assets/382e6a25-5562-4da6-b282-674ef9449181)


## MODEL GRAPH:
## LOW_PASS

![WhatsApp Image 2025-11-19 at 10 34 10_681adc81](https://github.com/user-attachments/assets/b7f37ba6-ae37-44d4-b716-1b6ad6b4eff9)

## HIGH-PASS

![WhatsApp Image 2025-11-19 at 10 34 12_8d55a603](https://github.com/user-attachments/assets/c21a27d1-979f-480d-a8d9-40fdd5d72a82)

## BAND-PASS

![WhatsApp Image 2025-11-19 at 10 34 12_0759a352](https://github.com/user-attachments/assets/455bd41b-ecd5-4838-a30e-dd0492a8c137)


## PROCEDURE - (LPF & HPF): 
1. Connect the circuit as shown in the circuit diagram. 
2. Select the corresponding cut-off frequency (higher or lower) and determine the value of C&R. 
select the value of R1 & Rf depending on desired passband gain Af.. 
3. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
4. Tabulate the output voltage Vo with respect to different values of input frequency. 
5. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to  get approximately the same characteristic as shown in the model graph. 
# PROCEDURE:BAND PASS FILTER 
1. Select the lower and higher cut-off frequency and calculate the value of R & C for the given 
frequencies. 
2. Design for LPF & HPF separately and then combine the circuit by first placing the HPF 
followed by a LPF (i.e) HPF in series with LPF. 
3. Connect the circuit as shown in the circuit diagram. 
4. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
5. Tabulate the output voltage Vo with respect to different values of input frequency. 
6. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to get approximately the same characteristic as shown in the model graph

## DESIGN:LPF & HPF:

<img width="429" height="324" alt="image" src="https://github.com/user-attachments/assets/b0f0ac0a-3006-494c-9096-e91ae2d6e87c" />

# DESIGN: BAND PASS FILTER
Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.  
1. Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency 
of HPF as fL = 1 KHz.  
2. Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf.  
Let C = 0.1μf.  
3. Calculate R from the expression.  
Given: fH = 2KHz  = 1/ (2πR1C1) 
   Let C1 = 0.1 µF, R1 = 7.9 KΩ 
Given: fL = 400Hz  = 1/ (2πR2C2) 
   Let C2 = 0.1 µF, R2 = 39.8 KΩ 
  Pass band Gain=4 
   Now   Ao = 1 + (Rf / R1)  
               2-1=(Rf / Ri) 
                Ri = Rf 
                 Let  Ri = Rf = 10 KΩ
## TABULATION:
## LOW_PASS

![WhatsApp Image 2025-11-19 at 10 34 11_061ae273](https://github.com/user-attachments/assets/edc0957c-b8d0-4676-ad0f-aed5fd8576ee)

## HIGH-PASS

![WhatsApp Image 2025-11-19 at 10 34 12_04921600](https://github.com/user-attachments/assets/6d8de808-cefa-4b35-88fe-bfb9c82ad101)

## BAND-PASS

![WhatsApp Image 2025-11-19 at 10 34 13_833c7f22](https://github.com/user-attachments/assets/320be38b-4b5c-4b1f-9957-a4bc6e0bd89b)


## GRAPH:
## LOW_PASS

![WhatsApp Image 2025-11-19 at 10 34 14_3378ac66](https://github.com/user-attachments/assets/bc4aa5c1-ef52-43d2-9bab-40259bfb798e)

## HIGH-PASS

![WhatsApp Image 2025-11-19 at 10 34 14_25d6e669](https://github.com/user-attachments/assets/f56ceca4-6e5a-4020-9af7-85a985240599)

## BAND-PASS

![WhatsApp Image 2025-11-19 at 10 34 15_337af4b2](https://github.com/user-attachments/assets/42b3df36-c4bc-422b-a974-a3d303b9a904)

 ## RESULTS:
Thus an Active Low pass, High pass and Band Pass Filters are designed and 
tested using op-amp IC 741. 

