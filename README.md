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

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
```
F(A,B,C,D)=AB+CD+AD

module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule
```


Developed by:LOHINI S

RegisterNumber:25015038 */


**RTL realization**
<img width="903" height="473" alt="image" src="https://github.com/user-attachments/assets/b7fb2696-243b-493b-9b63-c5d75bce6aeb" />

**Timing Diagram**
<img width="1600" height="860" alt="image" src="https://github.com/user-attachments/assets/1dd297c5-91ce-4181-bdb9-57d4489fccbd" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

