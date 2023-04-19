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
```
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: GOKUL T
RegisterNumber:  212222050015
Half adder program

module adder1(a,b,sum,carry);

input a,b;

output sum,carry;

xor(sum,a,b);

and(carry,a,b);

endmodule

Full adder program

module adder1(a,b,sum,carry);

input a,b;

output sum,carry;

xor(sum,a,b);

and(carry,a,b);

endmodule
```
Logic symbol & Truthtable
RTL realization

### Output:

### RTL
HALF ADDER
![image](https://user-images.githubusercontent.com/131269675/233107632-2237c511-a306-4f4a-aac2-0b76817f0b2b.png)

FULL ADDER
![image](https://user-images.githubusercontent.com/131269675/233108636-a250f57a-fbe3-4f1c-b815-070e65dbd5ae.png)


### TIMING DIAGRAM
HALF ADDER
![image](https://user-images.githubusercontent.com/131269675/233107917-ba384293-22b9-4744-9a21-957c2d81d003.png)

FULL ADDER
![image](https://user-images.githubusercontent.com/131269675/233107997-1dfab3a9-a874-4ff5-848f-74dd10648865.png)


### TRUTH TABLE 
HALF ADDER
![image](https://user-images.githubusercontent.com/131269675/233108102-a65e0a7d-a092-4adf-ba95-fcfb223b0190.png)

FULL ADDER
![image](https://user-images.githubusercontent.com/131269675/233108163-14d51644-4a11-4038-958c-ed6755584690.png)


### Result:
Thus the Implementation of Half Adder and Full Adder circuit are studied and the truth table for different logic gates are verified.
