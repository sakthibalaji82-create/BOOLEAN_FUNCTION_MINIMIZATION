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
F(A,B,C,D)=AB+CD+AD

```module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:magesh s RegisterNumber:25014866


**RTL realization**
![WhatsApp Image 2025-11-22 at 14 50 14_1bd5e836](https://github.com/user-attachments/assets/19cdbf9d-aeea-40c7-967f-ca6e3dbba08d)

**Output:**

**RTL**
![WhatsApp Image 2025-11-22 at 14 48 27_b9fbcd34](https://github.com/user-attachments/assets/c0c0f5bb-8117-405d-895f-2a68c46e22cb)

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

