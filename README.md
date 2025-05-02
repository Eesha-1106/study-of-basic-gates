### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B


**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B


**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**
```
Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by: Eesha ranka
 RegisterNumber: 212224240040
 ```
```
module exp1(A,B,C,D,E,F,G,H,I);
input A,B;
output C,D,E,F,G,H,I;
and(C,A,B);
or(D,A,B);
not(E,A);
nand(F,A,B);
nor(G,A,B);
xor(H,A,B);
xnor(I,A,B);
endmodule
```

 
**Logic symbol & Truthtable**

![image](https://github.com/user-attachments/assets/bc9ef6b5-6378-4b8a-9f6e-25afa605c65f)


**RTL realization Output:** 
![WhatsApp Image 2025-03-28 at 12 00 02_07d05f6c](https://github.com/user-attachments/assets/394a53bf-65f1-4232-b909-8ed45ba145e0)


**RTL**
![WhatsApp Image 2025-03-28 at 13 11 00_513245a1](https://github.com/user-attachments/assets/645382ed-4f58-4485-a253-4e5f5ff13b86)

**Result:**
Thus the truth table of logic gates in Quartus II using Verilog programming has been verified.


