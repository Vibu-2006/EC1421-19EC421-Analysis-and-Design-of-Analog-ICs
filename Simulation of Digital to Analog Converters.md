## EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
## SIMULATION OF DIGITAL TO ANALOG CONVERTER

## AIM:
To Design and simulate the digital to analog converter (DAC) circuit using LT Spice

## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1. Double click on LT Spice icon.

2. New schematic window open.

3. Pick and paste the required component from the library and draw the circuit diagram .

4. Complete the connection.

5. Select 1 voltage and select pulse width as 
Vinitial [V]: 5
       Von [V]: 0
       Tdelay [s]: 0
       Trise [s]: 1u
       Tfall [s]: 1u
               Ton [s]: 10m
        Tperiod [s]: 20m
        Ncycles: 100
Change the values of Ton = 20m , 40m, Tperiod  = 40m , 80m
For v2 and v3  keeping the other values constant.
6. Save the file by giving file name.

7. Click on the run option -->click advanced open -->select select transient analysis -->enter the amplitude time delay stop time value as (.tran 0 200 0 0.01).

8. Click on the run option -->simulation window opens-->place the probe -->output graph is obtained.

## CIRCUIT DIAGRAM AND OUTPUT GRAPH:
### DAC:
<img width="1918" height="1007" alt="Screenshot 2026-03-17 182814" src="https://github.com/user-attachments/assets/94c4b1ea-5c2b-42f8-9010-aed8b70bd37e" />
![WhatsApp Image 2026-03-26 at 11 16 02 AM](https://github.com/user-attachments/assets/e7218170-fd3c-4745-b721-ef9d70aea0c5)



## RESULT:
Thus the LT-SPICE tool has been studied and digital to analog converter (DAC) circuit is simulated.
