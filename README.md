# 5V-PROTECTION-CIRCUIT
Overvoltage Protection (OVP) Design 

![circuit (1)](https://github.com/user-attachments/assets/23767309-7363-4955-b36b-7e4dc2d119f0)

![image](https://github.com/user-attachments/assets/86b0a520-265c-40e6-a2bc-c17aa09e96ef)



WORKING PRINCIPLE:
 
Q1: P-MOSFET transistor to achieve ON & OFF state of the input power supply

D1: Zener diode with regulated voltage of 5.1V

If input voltage is less than or equal to 5V:

•	D1 is in cutoff mode

•	Emitter and base voltage of Q2 are both equal to input voltage, therefore Q2 is in cutoff state (Vbe<0.3V, which is equal to zero)

•	Gate of Q1 is pull down to ground through pull-down resistor(4.4kΩ)

•	Vs >Vg, which meet the conditions for P-MOS conduction

•	Therefore Q1 is conducting, Vo= Vin – Vdrop

![image](https://github.com/user-attachments/assets/0438b75f-982d-443c-8df0-fad3eac2fe99)

![image](https://github.com/user-attachments/assets/bce31765-e09e-4f1b-b8e7-9e963b3691d8)


If input voltage is greater than 5V:

•	D1 is in ON-STATE

•	Base voltage is stabilized at 5V

•	Emitter voltage increases with rising input voltage

•	When Ve reaches 5,7V, Q2 start conducting

•	Gate Of Q1 will be pulled up to to Ve , though Q2, making Vgs =0V

•	Therefor Q1 is not conducting

•	Vout= 0V

![image](https://github.com/user-attachments/assets/81d6c8a1-5177-4938-b0c0-f56da2067cbd)



![image](https://github.com/user-attachments/assets/0c80edab-c434-4f7a-a572-4a1fbcfcd80c)



