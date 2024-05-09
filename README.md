# EX NO:4
<P align='center'> <b>Implementation-of-Full-Adder-and-Full-subtractor-circuit</b>

**DATE:**

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

**Procedure**
```
1.Follow the same steps as for the full adder.
 2.Draw the full subtractor circuit using schematic design.
 3.The circuit includes XOR, AND, OR gates to perform subtraction.
 4.Compile, simulate, implement, and program the design similarly to the full adder.
 ```
**FULL ADDER**

**Program:**

![Screenshot 2024-04-27 103439](https://github.com/monish1545/FULL_ADDER_SUBTRACTOR/assets/166646660/f370d12f-92c0-4e28-bb9e-fe1cb41c019e)

**RTL Schematic**

![Screenshot 2024-04-27 103459](https://github.com/monish1545/FULL_ADDER_SUBTRACTOR/assets/166646660/4c173097-8283-47e4-8765-1236df35a63f)


**Truthtable**

![Screenshot 2024-04-27 103509](https://github.com/monish1545/FULL_ADDER_SUBTRACTOR/assets/166646660/c13e9702-fd24-4da7-be57-b15cc9135af4)



**Output Timing Waveform**

![Screenshot 2024-04-27 103527](https://github.com/monish1545/FULL_ADDER_SUBTRACTOR/assets/166646660/00513e9f-98fa-47ad-a56b-3dfd50dbbfa2)



**FULL SUBRACTOR**

**Program:**

![Screenshot 2024-04-27 103537](https://github.com/monish1545/FULL_ADDER_SUBTRACTOR/assets/166646660/1b4bbb82-37e5-4c03-ad83-2be374550395)

**RTL Schematic**

![Screenshot 2024-04-27 103546](https://github.com/monish1545/FULL_ADDER_SUBTRACTOR/assets/166646660/46e3e8bc-da73-4995-a9da-d7036b066e13)

**Truthtable**

![Screenshot 2024-04-27 103554](https://github.com/monish1545/FULL_ADDER_SUBTRACTOR/assets/166646660/5c44d4d1-d7fc-46ac-8249-4edbf116fd3d)

**Output Timing Waveform**

![Screenshot 2024-04-27 103603](https://github.com/monish1545/FULL_ADDER_SUBTRACTOR/assets/166646660/e82dea8f-e916-4062-aaa9-e4342f063f1e)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



