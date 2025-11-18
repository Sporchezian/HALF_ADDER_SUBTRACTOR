# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**
HALF ADDER:
<img width="1207" height="908" alt="Screenshot 2025-11-18 193041" src="https://github.com/user-attachments/assets/c50524d0-8a0c-41ba-93c2-ddf5f283f1cb" />

HALF SUBTRACTOR:
<img width="1197" height="896" alt="Screenshot 2025-11-18 193137" src="https://github.com/user-attachments/assets/f591809d-9797-466a-b397-ab34d0621d82" />

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: PORCHEZIAN S RegisterNumber: 25017994

**RTL Schematic**
HALF ADDER:
<img width="1660" height="831" alt="Screenshot 2025-11-18 111310" src="https://github.com/user-attachments/assets/b2927c1f-440d-4d0c-a9ee-65d8094c8b50" />

HALF SUBTRACTOR:
<img width="1649" height="806" alt="Screenshot 2025-11-18 113343" src="https://github.com/user-attachments/assets/7c2f496b-4794-48b9-b1e2-cfb149be287c" />

**Output/TIMING Waveform**
HALF ADDER:
<img width="1909" height="317" alt="Screenshot 2025-11-18 111604" src="https://github.com/user-attachments/assets/27df7774-844d-4a38-9c99-3f22f3e7dc17" />

HALF SUBTRACTOR:
<img width="1837" height="251" alt="Screenshot 2025-11-18 113531" src="https://github.com/user-attachments/assets/1b75764f-aeb6-4a1b-8991-7ca899f67332" />

**Result:**
Hence to design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming has been executed successfully.
