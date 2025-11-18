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
<img width="1207" height="908" alt="Screenshot 2025-11-18 193041" src="https://github.com/user-attachments/assets/544d0dbb-ac9c-4fab-b48f-c3c0fdd90dbc" />

HALF SUBTRACTOR:
<img width="1197" height="896" alt="Screenshot 2025-11-18 193137" src="https://github.com/user-attachments/assets/1bc4587c-1127-4c3c-99b4-bcfb4fab544f" />

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: PORCHEZIAN S 

RegisterNumber: 25017994

HALF ADDER:
```
module exp3a(a,b,s,c);
input a,b;
output s,c;
xor g1(s,a,b);
and g2(c,a,b);
endmodule
```

HALF SUBTRACTOR:
```
module exp3b(a,b,diff,borr);
input a,b;
output diff,borr;
assign diff=a^b;
assign borr=(~a)&b;
endmodule
```
**RTL Schematic**
HALF ADDER:
<img width="1660" height="831" alt="Screenshot 2025-11-18 111310" src="https://github.com/user-attachments/assets/caf04791-f785-4ef0-9435-6ef331ff13bd" />


HALF SUBTRACTOR:
<img width="1649" height="806" alt="Screenshot 2025-11-18 113343" src="https://github.com/user-attachments/assets/990c4e3b-d015-42e5-9f4f-63be1f6d0bee" />


**Output/TIMING Waveform**
HALF ADDER:
<img width="1909" height="317" alt="Screenshot 2025-11-18 111604" src="https://github.com/user-attachments/assets/0443ced8-75ed-4a17-8164-5363e149831d" />

HALF SUBTRACTOR:
<img width="1837" height="251" alt="Screenshot 2025-11-18 113531" src="https://github.com/user-attachments/assets/b0a46400-5a3d-429f-a1bf-9fe90bab8af2" />

**Result:**

Hence to design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming has been verified successfully.
