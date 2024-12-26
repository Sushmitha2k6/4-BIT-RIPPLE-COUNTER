EXP12 4-BIT-RIPPLE-COUNTER

NAME:SUSHMITHA S

REF NO:24008099

**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 BIT RIPPLE COUNTER:**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

**PROCEDURE:**


 1. Type the program in Quartus software.
 2. Compile and run the program.
 3. Generate the RTL schematic and save the logic diagram.
 4. Create nodes for inputs and outputs to generate the timing diagram.
 5. For different input combinations generate the timing diagram. 


**PROGRAM**



![12](https://github.com/user-attachments/assets/05de7575-e54c-4c02-b46a-9b2a81e62b31)



**RTL LOGIC FOR 4 BIT RIPPLE COUNTER:**



![Screenshot 2024-12-26 185250](https://github.com/user-attachments/assets/c5611e3a-85be-4200-a782-1eb80230af90)





**TIMING DIGRAMS FOR 4 BIT RIPPLE COUNTER:**




![Screenshot 2024-12-26 185237](https://github.com/user-attachments/assets/25da335e-bea2-4e93-ac4c-5ac888cddec8)



**RESULT:**

 Thus,to implement 4 Bit Ripple Counter using verilog and validating 
their functionality using their functional tables is verified.
