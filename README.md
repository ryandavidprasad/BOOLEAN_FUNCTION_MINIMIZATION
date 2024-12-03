# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

![image](https://github.com/user-attachments/assets/d8a999d9-ef1b-445d-bf7a-9fc5d7684234)
![image](https://github.com/user-attachments/assets/6f92eec1-0249-4c0e-986b-dc34958c86d9)


**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
module exp2(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Ryan David Prasad RegisterNumber:24004080*/


**RTL realization**

**Output:**
![image](https://github.com/user-attachments/assets/38f23f9c-5344-4fd4-bca9-3e40f6a33e73)


**RTL**

**Timing Diagram**
![image](https://github.com/user-attachments/assets/c4a6ee5c-8ba7-40a6-82a1-ec29aa2f6573)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

