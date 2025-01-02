## NAME:MANIMARAN V
## REGISTER NO:24008541
# EXP 3:IMPLEMENTATION OF HALF ADDER SUBTRACTOR



# AIM:

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

# EQUIPMENTS REQUIRED:

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

# HALF ADDER

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

# HALF SUBTRACTOR

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

# TRUTH TABLE
![Screenshot 2024-12-09 114427](https://github.com/user-attachments/assets/0cc57130-3f09-4121-8885-a55f38280de4)


# PROCEDURE

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


# PROGRAM:
Half adder
![Screenshot (51)](https://github.com/user-attachments/assets/829c7400-f679-4b62-a3ed-7c12e726ef4c)
Half subtractor
![Screenshot (54)](https://github.com/user-attachments/assets/cec946a2-f492-4770-a8a2-66637c5c478a)



# RTL OUTPUT
Half adder
![Screenshot (52)](https://github.com/user-attachments/assets/4884d710-0f8a-4c6a-9db1-bdcf6eaf8f34)
Half subtractor
![Screenshot (53)](https://github.com/user-attachments/assets/5eb1e098-2adc-4899-a6ba-32f4985808b3)




# WAVEFORM
Half adder
![Screenshot (50)](https://github.com/user-attachments/assets/ad92f06e-dd62-47e2-a8ba-c02806efe57d)
Half subtractor
![Screenshot (55)](https://github.com/user-attachments/assets/0e359a2b-37a2-498c-a4ef-6b95036d2a4d)



# RESULT
Thus the given logic functions are implemented using Quartus II and their operations are verified using Verilog programming.
