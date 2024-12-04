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

```
**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:S.Dharshini
 RegisterNumber:*/24901197
```
```
module exe_2(f_and,f_or,f_not,f_nor,f_nand,f_xor,f_xnor,a,b);
input a,b;
output f_and,f_or,f_not,f_nor,f_nand,f_xor,f_xnor;
and(f_and,a,b);
or(f_or,a,b);
not(f_not,a);
nand(f_nand,a,b);
nor(f_nor,a,b);
xor(f_xor,a,b);
xnor(f_xnor,a,b);
endmodule
```


**Output:**
![WhatsApp Image 2024-12-04 at 09 04 13_1ec464fb](https://github.com/user-attachments/assets/e9ed2155-bbba-4aa5-bce4-34b17aab5a33)

**Timing Diagram**
![WhatsApp Image 2024-12-04 at 09 07 04_2d3d458e](https://github.com/user-attachments/assets/79ae52d0-d572-425b-a9e3-695492dd958f)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

