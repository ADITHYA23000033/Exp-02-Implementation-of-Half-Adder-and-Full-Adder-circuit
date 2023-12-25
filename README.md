# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:

/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:ADITHYA V

RegisterNumber: 23000033 
*/

half adder

![Exp3 ha code](https://github.com/ADITHYA23000033/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514544/4b905c93-8466-4995-9ce2-fce8e5524fba)

full adder

![Exp3 fa code](https://github.com/ADITHYA23000033/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514544/e656eb4e-6c36-41aa-bed2-c630fa00e3f8)



### Output:
RTL:

half adder

![Exp3 ha RTL diagram](https://github.com/ADITHYA23000033/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514544/33ce53c5-866d-457a-a944-8457bb20653c)

full adder

![Exp3 fa RTL diagram](https://github.com/ADITHYA23000033/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514544/9eb8932d-6482-4e80-bdfb-3cca36dd9a37)


### TIMING DIAGRAM

half adder

![exp3 ha wave](https://github.com/ADITHYA23000033/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514544/e7a96112-ead6-43b6-9eec-6767f54b5224)

full adder

![exp 3 fa wave](https://github.com/ADITHYA23000033/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514544/9d7a2b21-cf6f-4baa-9023-f27f059c82ae)


### TRUTH TABLE :

half adder

![Exp3 truthtable (ha)](https://github.com/ADITHYA23000033/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514544/b2ad43e6-e4cb-4a66-8bb2-b823c3143b19)

full adder

![Exp3 truthtable (fa)](https://github.com/ADITHYA23000033/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514544/bf3a59da-0cad-4282-ab1d-cdba18fe6fc3)

### Result:

Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus
using Verilog programming.
