## Name:V.Sarishvarshan.
## Reg:23012018


## Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor:
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor:
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure



Write the detailed procedure here 


## Program:


## Half Subtractor:


![Screenshot 2023-12-29 202307](https://github.com/sarishvarshan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152167665/e210ecd1-4847-48a5-ba60-8a2b232048a2)



## Full Subtractor:

![Screenshot 2023-12-29 202318](https://github.com/sarishvarshan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152167665/3f67c948-c091-431a-9f40-2d46db7c8365)


Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: 

## Truthtable


## Half Subtractor:

![Screenshot 2023-12-29 202332](https://github.com/sarishvarshan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152167665/6c2d1a39-0a8c-4c16-ac2f-e9b2e2da22fe)


## Full Subtractor:


![Screenshot 2023-12-29 202511](https://github.com/sarishvarshan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152167665/75a92053-dd39-4d56-a590-5581de5b1a63)


##  RTL realization


## Half Subtractor:

![Screenshot 2023-12-29 202538](https://github.com/sarishvarshan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152167665/7cffb287-f587-4a63-8307-f7312aedf980)


## Full Subtractor:

![Screenshot 2023-12-29 202549](https://github.com/sarishvarshan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152167665/4324a120-f7d7-496f-a71a-677682f8111c)

## Timing diagram 


## Half Subtractor:

![Screenshot 2023-12-29 202600](https://github.com/sarishvarshan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152167665/335d4900-6d0e-457f-9143-893b8e2228d3)


## Full Subtractor:
![Screenshot 2023-12-29 202610](https://github.com/sarishvarshan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152167665/f5942798-52fb-4c42-b0e1-9d9567c1e47f)



## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
