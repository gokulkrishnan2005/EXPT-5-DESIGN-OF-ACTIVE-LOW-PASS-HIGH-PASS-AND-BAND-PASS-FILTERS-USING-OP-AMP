![121abe88-45a2-436e-894b-cbcb06016f7c](https://github.com/user-attachments/assets/ed912e3c-7bb4-4bb7-bf38-576d4b7ae384)# EXPT-5-DESIGN-OF-ACTIVE-LOW-PASS-HIGH-PASS-AND-BAND-PASS-FILTERS-USING-OP-AMP

# AIM:

To design and obtain the frequency response of
i) First order Low Pass Filter (LPF)
ii) First order High Pass Filter (HPF)
iii) Band pass filter

# APPARATUS REQUIRED:
<img width="951" height="255" alt="image" src="https://github.com/user-attachments/assets/0be75f46-a2db-4722-bc15-3e26cf590cd0" />

# THEORY:
# LOW PASS FILTER

A LPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.

# CIRCUIT DIAGRAM: LOW PASS FILTER
<img width="535" height="292" alt="image" src="https://github.com/user-attachments/assets/0efc7257-2117-4c25-b231-9811d694566a" />

# MODEL GRAPH:
<img width="586" height="359" alt="image" src="https://github.com/user-attachments/assets/429258e6-e209-49ea-9b47-38a835a30253" />

# DESIGN:
Design a second oder Butterworth filter with thw upper cutoff frequency of 1KHz.
![121abe88-45a2-436e-894b-cbcb06016f7c](https://github.com/user-attachments/assets/13b836c4-2402-4aa6-9188-1bd207b4dc6d)

# TABULATION:
![c7638ca3-af84-417e-a959-bd259baf5a0a](https://github.com/user-attachments/assets/f4e8bc33-d558-43dd-b66e-498e71199719)

# GRAPH:
![01baded8-e6c1-4d2d-9056-e3b965957062](https://github.com/user-attachments/assets/c26ed535-c614-45af-a7b2-460815057d97)

# THEORY:
# HIGH PASS FILTER

A LPF allows frequencies from 0 to higher cut of frequencThe frequency at which the magnitude of the gain is 0.707 times the maximum value of gain is called low cut off frequency. Obviously, all frequencies higher than fL are pass band frequencies with the highest frequency determined by the closed –loop band width all of the op- amp.

# CIRCUIT DIAGRAM: HIGH PASS FILTER
<img width="533" height="314" alt="image" src="https://github.com/user-attachments/assets/1090306e-34c0-45db-8250-ad354d83d83b" />


# MODEL GRAPH:
<img width="695" height="337" alt="image" src="https://github.com/user-attachments/assets/5b67fa34-f791-4cf2-a4aa-b139eb9bba51" />


# DESIGN:
Design a second oder Butterworth filter with thw lower cutoff frequency of 1KHz.
![121abe88-45a2-436e-894b-cbcb06016f7c](https://github.com/user-attachments/assets/fb24b827-74d0-42ab-b894-e8caf59b6cb0)

# TABULATION:
![401dcfdc-50b8-41a0-84c4-273b3ed99cf8](https://github.com/user-attachments/assets/5913f9c0-dd0a-4599-ab69-586db84c836a)

# GRAPH:
![dbe52ec9-6826-47fb-85d8-09a2ace829d0](https://github.com/user-attachments/assets/a63bff19-4bbf-4516-8bdd-40b6f5289cf2)

# THEORY:
# BAND PASS FILTER

A band pass filter has a pass band between two cutoff frequencies fH and fL such that fH > fL. Any input frequency outside this pass band is attenuated. There are two types of band-pass filters. Wide band pass and Narrow band pass filters. We can define a filter as wide band pass if its quality factor Q <10. If Q>10, then we call the filter a narrow band pass filter. A wide band pass filter can be formed by simply cascading high-pass and low-pass sections. The order of band pass filter depends on the order of high pass and low pass sections.

# CIRCUIT DIAGRAM: BAND PASS FILTER
<img width="602" height="257" alt="image" src="https://github.com/user-attachments/assets/89b232eb-3bc6-4784-bad4-bf40f78031ed" />

# MODEL GRAPH:
<img width="1037" height="460" alt="image" src="https://github.com/user-attachments/assets/052fae74-cf20-4911-bbe6-92cf576a1b63" />


# DESIGN:
Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.
![c03912e5-0487-4433-b924-8d502a36e6c7](https://github.com/user-attachments/assets/0b370413-cc55-4034-b897-48c69b184fb8)
![b96b8d37-8aca-4dad-bf63-b7590d0c0ca0](https://github.com/user-attachments/assets/713dfe01-31d1-40a7-b63e-f6748914c56f)

# TABULATION:
![2e33cfb2-aa7d-49ee-bb70-78c363450b1f](https://github.com/user-attachments/assets/778a14ff-74df-406a-95ea-5e124c7dee84)


# GRAPH:
![eefeb517-abed-45b2-a149-97541cd5f853](https://github.com/user-attachments/assets/22c18200-3cea-4f85-8181-60f7a8bafd16)

# PROCEDURE - (LPF & HPF):
1. Connect the circuit as shown in the circuit diagram.
2. Select the corresponding cut-off frequency (higher or lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4. Tabulate the output voltage Vo with respect to different values of input frequency.
5. Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.

# PROCEDURE:BAND PASS FILTER
1. Select the lower and higher cut-off frequency and calculate the value of R & C for the given frequencies.
2. Design for LPF & HPF separately and then combine the circuit by first placing the HPF followed by a LPF (i.e) HPF in series with LPF.
3. Connect the circuit as shown in the circuit diagram.
4. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
5. Tabulate the output voltage Vo with respect to different values of input frequency.
6. Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.


# RESULT
![e3c81449-d22a-4d17-b37f-ad07fd429f04](https://github.com/user-attachments/assets/c99cadb4-c0be-4212-9eba-9bdb84afb9f4)
