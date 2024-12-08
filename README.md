# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**
![Screenshot 2024-12-08 060913](https://github.com/user-attachments/assets/2cfdeb33-8849-4879-acaf-b49c14cfe204)

**Procedure**

1. Type the program in Quartus software.
2. Compile and run the program.
3. Generate the RTL schematic and save the logic diagram.
4. Create nodes for inputs and outputs to generate the timing diagram.
5. For dierent input combinations generate the timing diagram.
 

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: SANTHIYA B
RegisterNumber: 24900724
![Screenshot 2024-12-08 060927](https://github.com/user-attachments/assets/3cad85f6-a61b-441e-9e5c-854ca307c3e3)


**RTL Schematic**
full adder
![Screenshot 2024-12-08 061017](https://github.com/user-attachments/assets/2b150d9e-7541-4074-929b-7085f67698f2)
full subtractor
![Screenshot 2024-12-08 061041](https://github.com/user-attachments/assets/1980dfbb-05ee-456d-940d-202e1fb6f0f4)

**Output Timing Waveform**
full adder
![Screenshot 2024-12-08 061131](https://github.com/user-attachments/assets/fe7ad556-7f7b-4750-94fa-6e66ca979fe4)
full subtractor
![Screenshot 2024-12-08 061147](https://github.com/user-attachments/assets/d4579100-2885-4a53-b0fe-8e6ed2343e42)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



