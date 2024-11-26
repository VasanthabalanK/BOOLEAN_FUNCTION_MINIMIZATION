# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
~~~
module exp2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule
~~~
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Vasanthabalan K RegisterNumber:24900992*/


**RTL realization**
![exp2](https://github.com/user-attachments/assets/78f30a6f-fcc9-4d78-866c-0226282a0403)


**Timing Diagram**
![Screenshot 2024-11-06 135026](https://github.com/user-attachments/assets/9182442b-4127-4bba-9044-cdeb8ce644d8)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

