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

![Screenshot 2025-04-23 133047](https://github.com/user-attachments/assets/5b107cbf-ae68-4ab8-9472-ba5e7aae472c)


![Screenshot 2025-04-23 133055](https://github.com/user-attachments/assets/9481d4db-c256-4f26-a0f5-a5ad9a8c23d8)


**Procedure**

 1. Type the program in Quartus software.
 2. Compile and run the program.
 3. Generate the RTL schematic and save the logic diagram.
 4. Create nodes for inputs and outputs to generate the timing diagram.
 5. For different input combinations generate the timing diagram.

**Program:**

![Screenshot 2025-04-23 133718](https://github.com/user-attachments/assets/3a777956-f3e7-4d75-a64c-953ab87f7af2)


![WhatsApp Image 2025-04-23 at 10 07 10_04123f4b](https://github.com/user-attachments/assets/f8366fd9-d0bd-4fd7-a408-14528adaf9aa)


/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.*/

**RTL Schematic**

![Screenshot 2025-04-23 134133](https://github.com/user-attachments/assets/d6835455-fbf1-4f24-bce8-53538aad5a64)

![Screenshot 2025-04-23 132814](https://github.com/user-attachments/assets/66e4ee18-82d5-4b3f-9733-2286ae9ff39c)

**Output Timing Waveform**

![Screenshot 2025-04-23 134531](https://github.com/user-attachments/assets/ba2101af-28c9-4b40-84df-63a467933be3)


![Screenshot 2025-04-23 134451](https://github.com/user-attachments/assets/61c21be9-2c8e-457a-8b0c-0b2115c4faee)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



