# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Developed by:

J.Nandakesore

## Register Number:

23009689

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin


## Procedure

1.Use module projname(input,output) to start the Verilog programmming.

2.Assign inputs and outputs using the word input and output respectively.

3.Use defined keywords like wire,assign and required logic gates to represent the boolean expression.

4.Use each output to represnt onre for differnce and the other for borrow.

5.End the verilog program using keyword endmodule

## Program:

Half Subractor:

![image](https://github.com/Nandakesore0210/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365088/3c7a1100-8a4c-4beb-90f4-754634957c79)

Full Subractor:

![image](https://github.com/Nandakesore0210/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365088/91a1b3fd-5c25-4852-8c89-361e053a9bb7)

## Truthtable

Half Subractor:

![image](https://github.com/Nandakesore0210/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365088/a9d9d466-c1a2-4ca3-b1ad-128c299ee7f8)

Full Subractor:

![image](https://github.com/Nandakesore0210/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365088/95259da9-cb48-494f-b2ed-62e88a7d2442)

##  RTL realization:

Half Subractor:

![image](https://github.com/Nandakesore0210/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365088/48292da1-21da-410d-a8b0-2692f0310d00)

Full subractor:

![image](https://github.com/Nandakesore0210/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365088/9fa74004-c03d-4e11-b32c-7d47b54e4422)

## Timing diagram:

Half Subractor:

![image](https://github.com/Nandakesore0210/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365088/824a950e-133d-4bf9-a8d4-5200dc748aa3)

Full Subractor:

![image](https://github.com/Nandakesore0210/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149365088/ca181b8a-0cfe-4125-b520-89da9fd00680)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
