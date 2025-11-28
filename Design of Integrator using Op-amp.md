# EC1421 - 19EC421 - Analysis-and-Design-of-Analog-ICs
# Design of Integrator using Op-amp.

## AIM:
To design and test the performance of integrator circuits using  Op-amp.

## APPARATUS REQUIRED:

<img width="811" height="206" alt="image" src="https://github.com/user-attachments/assets/fd527bf4-b7bf-4330-9b09-ce7ad607bdeb" />


## THEORY:

INTEGRATOR 
 
A circuit in which the output voltage waveform is the integral of the input voltage 
waveform is the integrator. Such a circuit is obtained by using a basic inverting amplifier 
configuration if the feedback resistor Rf is  replaced by a capacitor Cf .  The expression for the 
output voltage is given as, 

Vo = - (1/Rf C1 ) ∫ Vi dt 
 
Here the negative sign indicates that the output voltage is 180 0 out of phase with the 
input signal. Normally between fa and fb the circuit acts as an integrator. Generally, the value of 
fa < fb . The input signal will be integrated properly if the Time period T of the signal is larger 
than or equal to Rf Cf .

That is, T ≥ Rf Cf 
 
The integrator is most commonly used in analog computers and ADC and signal-wave 
shaping circuits.


## DESIGN
~~~
To obtain the output of an Integrator circuit with component values R1Cf = 0.1ms , Rf = 10 
R1 and Cf = 0.01 µF and also if 1 V peak square wave at 1000Hz is applied as input. 
We know the frequency at which the gain is 0 dB, fb = 1 / (2π R1 Cf) Therefore fb =    
Since fb = 10 fa , and also the gain limiting frequency fa = 1 / (2π Rf Cf) 
We get , R1 =  and hence Rf =

~~~
## CIRCUIT DIAGRAM:

![WhatsApp Image 2025-11-14 at 11 28 18_fad82b8f](https://github.com/user-attachments/assets/c5c603a7-d74d-4f57-86b6-a6e2ccab35cf)


## MODEL GRAPH

![WhatsApp Image 2025-11-14 at 11 28 17_8dc27c71](https://github.com/user-attachments/assets/5c485428-6671-4fe0-b65a-09e69899024f)


## PROCEDURE:

1. Connections are given as per the circuit diagram 
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC. 
3. By adjusting the amplitude and frequency knobs of the function generator, appropriate 
input voltage is applied to the inverting input terminal of the Op- Amp. 
4. The output voltage is obtained in the CRO and the input and output voltage waveforms 
are plotted in a graph sheet.

## TABULATION:

![WhatsApp Image 2025-11-14 at 11 28 18_38744d07](https://github.com/user-attachments/assets/bd01c667-7e7c-4415-ab6b-3f95f8c7a74d)


## GRAPH:

![WhatsApp Image 2025-11-14 at 11 28 13_9b2d5290](https://github.com/user-attachments/assets/0f5690e2-c433-414d-b930-6da9d61e1081)


## RESULT:

Thus an Integrator using op-amp are designed and their performance was successfully tested using op-amp IC 741. 
