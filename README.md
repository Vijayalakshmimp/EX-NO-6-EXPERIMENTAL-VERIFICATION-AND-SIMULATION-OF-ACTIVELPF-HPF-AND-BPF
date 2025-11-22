# EX-NO-6-EXPERIMENTAL-VERIFICATION-AND-SIMULATION-OF-ACTIVELPF-HPF-AND-BPF
## 6 DESIGN OF ACTIVE LOW PASS, HIGH PASS AND BAND PASS FILTERS USING OP-AMP
         
---

## AIM
            

         
---

## AIM and obtain the frequency response of

i)	First order Low Pass Filter (LPF)
ii)	First order High Pass Filter (HPF)
iii)	Band pass filter

---

## ** 6 A :- LOW PASS FILTER**
## DATE: 27.09.2025


## THEORY
## LOW PASS FILTER
A LPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.
## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1.6K,10K,0.1 µF | 1 |
| 7 | Connecting wires and probes | As required | — |

---
## CIRCUIT DIAGRAM
![IMG-20251122-WA0035 1](https://github.com/user-attachments/assets/c79589f7-1f9d-4407-bb7f-169cf4dfd92b)

## SIMULATION CIRCUIT DIAGRAM
<img width="1250" height="884" alt="image" src="https://github.com/user-attachments/assets/a330880d-cd8f-4c0d-bd52-35ceb8c7fe9b" />




## MODEL GRAPH
![IMG-20251122-WA0036 1](https://github.com/user-attachments/assets/52ae7d15-b84f-47af-9696-7f9b46b7836b)

---

## DESIGN

Given: fH = 1 KHz = 1/ (2πRC) Let C = 0.1 µF, R = 1.6 KΩ
For n = 2, α (damping factor) = 1.414, Passband gain = Ao = 3 - α =3 – 1.414 = 1.586.
Transfer function of second order butterworth LPF as:
1.586
 
H(s) =
 
S2 + 1.414 s + 1
 
Now	Ao = 1 + (Rf / R1) = 1.586 = 1 + 0.586
Let Ri = 10 KΩ, then Rf = 5.86 KΩ


## PROCEDURE

PROCEDURE - (LPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency  lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION
![IMG-20251122-WA0038 1](https://github.com/user-attachments/assets/8bfd039f-e8c9-458a-9a61-6c23a6ff2b2d)

		

---

## OUT PUT WAVEFORM AND DISCUSSION 
![IMG-20251122-WA0037 1](https://github.com/user-attachments/assets/8837a62d-9809-4ad2-93a9-05ef10a1aa9a)

## SIMULATION WAVEFORM
<img width="1903" height="446" alt="image" src="https://github.com/user-attachments/assets/3366455d-8da4-4017-8844-a3a29afefac4" />


---

 ## 6 B HIGH PASS FILTER
## DATE: 04.10.2025
---

## THEORY
HIGH PASS FILTER
A HPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1.6K,10K,5.86K, 0.1 µF | 1 |
| 7 | Connecting wires and probes | As required | — |


## CIRCUIT DIAGRAM
![IMG-20251122-WA0040 1](https://github.com/user-attachments/assets/7a7b85c8-1897-4d20-b17c-5ffb3c98147c)

## SIMULATION CIRCUIT DIAGRAM
<img width="1334" height="836" alt="image" src="https://github.com/user-attachments/assets/e655b0a1-6b47-47e9-9f79-f0e883569d76" />


## MODEL GRAPH
![IMG-20251122-WA0039 1](https://github.com/user-attachments/assets/492e1998-4080-4d83-a7df-65022302b34b)



---

## DESIGN

Given: fH = 1 KHz = 1/ (2πRC) Let C = 0.1 µF, R = 1.6 KΩ
For n = 2, α (damping factor) = 1.414, Passband gain = Ao = 3 - α =3 – 1.414 = 1.586.
Transfer function of second order butterworth LPF as:
1.586
 
H(s) =
 
S2 + 1.414 s + 1
 
Now	Ao = 1 + (Rf / R1) = 1.586 = 1 + 0.586
Let Ri = 10 KΩ, then Rf = 5.86 KΩ


## PROCEDURE

PROCEDURE - ( HPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency ( lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

![IMG-20251122-WA0042 1](https://github.com/user-attachments/assets/04389fec-8a81-49aa-bdfe-5791a4c33029)

---

## OUT PUT WAVEFORM AND DISCUSSION 
![IMG-20251122-WA0041 1](https://github.com/user-attachments/assets/027f2140-90ba-4221-af70-86237b284b8d)

## SIMULATION WAVEFORM
<img width="1909" height="437" alt="image" src="https://github.com/user-attachments/assets/e36db088-b991-46d5-be50-cbd1cddcb2b5" />

---

 ## 6C Band Pass Filter
## DATE: 11.10.2025
---

## THEORY
 ##Band Pass Filter
A BPF allows frequencies in between lower cut of frequency and higher cut of frequency, fH-fL. A band-pass (BP) filter passes frequencies in a band fL_fH and attenuates below fL and above fH.. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors |10K,38.8K,7.9K,0.01uf | 1 |
| 7 | Connecting ires and probes | As required | — |


## CIRCUIT DIAGRAM
![IMG-20251122-WA0043 1](https://github.com/user-attachments/assets/74197fe5-093f-40f0-b33c-b444a3154717)

## SIMULATION CIRCUIT DIAGRAM

<img width="1497" height="863" alt="image" src="https://github.com/user-attachments/assets/b9ad9ed7-de91-4050-9028-8680f854de61" />



## MODEL GRAPH

![IMG-20251122-WA0044 1](https://github.com/user-attachments/assets/d8d654da-839c-4e72-b312-957f7ebba2fe)



---

## DESIGN

DESIGN: BAND PASS FILTER

Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.
1.	Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency of HPF as fL = 1 KHz.
2.	Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf. Let C = 0.1μf.
3.	Calculate R from the expression. Given: fH = 2KHz = 1/ (2πR1C1) Let C1 = 0.1 µF, R1 = 7.9 KΩ
Given: fL = 400Hz = 1/ (2πR2C2)
Let C2 = 0.1 µF, R2 = 39.8 KΩ
Pass band Gain=4
Now		Ao = 1 + (Rf / R1) 2-1=(Rf / Ri)
Ri = Rf
Let Ri = Rf = 10 KΩ


## PROCEDURE

PROCEDURE:BAND PASS FILTER
1.	Select the lower and higher cut-off frequency and calculate the value of R & C for the given frequencies.
2.	Design for LPF & HPF separately and then combine the circuit by first placing the HPF followed by a LPF (i.e) HPF in series with LPF.
3.	Connect the circuit as shown in the circuit diagram.
4.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
5.	Tabulate the output voltage Vo with respect to different values of input frequency.
6.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

![IMG-20251122-WA0046 1](https://github.com/user-attachments/assets/76cb3161-400d-48ef-8265-531b45dee158)

---

## OUT PUT WAVEFORM AND DISCUSSION 

![IMG-20251122-WA0045 1](https://github.com/user-attachments/assets/7c7435c2-81fd-43ad-8a55-79f96c34a7ec)

## SIMULATION WAVEFORM

<img width="1901" height="441" alt="image" src="https://github.com/user-attachments/assets/28dd2968-6247-4539-82e4-88fc8311d3da" />

---
##RESULT:
	Thus an Active Low pass, High pass and Band Pass Filters are designed and
tested using op-amp IC 741.
---

   
