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

i)
```
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```


ii)
```
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

Developed by:magesh s 
RegisterNumber:25014866

**Output:**

**RTL**
<img width="1036" height="557" alt="Screenshot 2025-12-15 083845" src="https://github.com/user-attachments/assets/e74043ea-8f12-4694-b341-7cf9f0e45ce8" />

<img width="1035" height="552" alt="Screenshot 2025-12-15 083915" src="https://github.com/user-attachments/assets/ce1c3c29-0a25-4cfd-86ee-1a67f84e1c65" />

**Timing Diagram**

<img width="1037" height="522" alt="Screenshot 2025-12-15 084005" src="https://github.com/user-attachments/assets/a8221110-7e9c-4979-87e4-df3da373073b" />

<img width="1034" height="526" alt="Screenshot 2025-12-15 084033" src="https://github.com/user-attachments/assets/a619ed4b-16bf-4517-9911-76a975610888" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

