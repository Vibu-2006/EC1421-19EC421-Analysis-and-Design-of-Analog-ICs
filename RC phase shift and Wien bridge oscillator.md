# EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
## RC PHASE SHIFT AND WIEN BRIDGE OSCILLATOR

## AIM:
To construct a RC phase shift and Wien bridge oscillator to generate sine wave using op-amp.

## APPARATUS REQUIRED:
<img width="933" height="270" alt="image" src="https://github.com/user-attachments/assets/4f7bc183-2ed0-4591-b9aa-846127704eee" />

## THEORY:
### RC PHASE SHIFT OSCILLATOR:
RC phase shift oscillator produces 360° of phase shift in two parts. Firstly,each and every RC pair in the feedback network produces 60° phase shift and totally there were three pairs, thus producing 180° Phase shift and secondly, the feedback input is given to the inverting terminal of op-amp to produce another 180° phase shift and a total phase shift of 360°.
The frequency of oscillation is given by fo = 1 /  6 (2RC ).If an inverting amplifier is used, the gain must be atleast equal to 29 to ensure the oscillations with constant .
### WIEN BRIDGE:
A bridge circuit with two components connected in series and parallel combination is used to archived the required of phase shift of 0o. When the bridge is balanced the phase shift of 0o is achieved and the feedback signal is connected to the positive terminal; of Op-amp. So the Op-amp is acting as a non-inverting amplifier and the feedback network do not provide any phase shift.
The frequency of oscillation is given by fo = 1/2πRC

## CIRCUIT DIAGRAM:
<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/5a0fe384-447d-4970-b612-0031b80f21aa" />
<img width="1600" height="1199" alt="image" src="https://github.com/user-attachments/assets/3dfbb72f-4d90-448b-b80c-1702f512eae7" />


## MODEL GRAPH:
<img width="1599" height="1200" alt="image" src="https://github.com/user-attachments/assets/c8b04a7f-b568-4906-ac5b-2baab1f907c2" />


## PROCEDURE:
1. Connect the circuit as shown in fig. With the design values.
2. Observe the output waveforms using a DSO.For obtaining sine wave adjust Rf.
3. Measure the output wave frequency and amplitude.
   
## DESIGN:
<img width="645" height="758" alt="image" src="https://github.com/user-attachments/assets/d2e7cd3f-8c88-44aa-8ac3-807b92beabba" />

## TABULATION:
<img width="1599" height="1200" alt="image" src="https://github.com/user-attachments/assets/3b525316-3dde-4f5c-bec3-bd8145286486" />
<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/069187a3-c08b-4c30-b0a5-5eb7e0400010" />



## GRAPH:
<img width="1200" height="1599" alt="image" src="https://github.com/user-attachments/assets/cded182c-88b9-48ea-a889-951ecad473bc" />


## RESULT:
Thus the RC Phase Shift and Wien Bridge oscillators are designed and tested using op-amp IC 741.
