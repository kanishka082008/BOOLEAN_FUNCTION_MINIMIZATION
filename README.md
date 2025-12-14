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
i) module funct1(a,b,c,d,f1); input a,b,c,d; output f1; assign f1=((~b & ~d)|(~a & b & d)|(a & b &
~c)); endmodule
ii) module funct2(w,x,y,z,f2); input w,x,y,z; output f2; assign f2=((~y & z)|( w & y )|(x & y)); endmodule

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/


**RTL realization**
<img width="1053" height="520" alt="Screenshot 2025-12-14 112710" src="https://github.com/user-attachments/assets/0bf297a5-c17c-42ba-8be1-71dbde6619c8" />





**Output:**
<img width="1108" height="582" alt="Screenshot 2025-12-14 112800" src="https://github.com/user-attachments/assets/bb596b47-f014-44ea-94ec-4a61488edb4e" />
<img width="1121" height="580" alt="Screenshot 2025-12-14 112819" src="https://github.com/user-attachments/assets/611c80d8-e17e-45c6-9b06-4b5a7334a3f8" />




**RTL**
<img width="1360" height="427" alt="Screenshot 2025-12-14 112847" src="https://github.com/user-attachments/assets/70a33e7c-5ef9-4bcc-bdab-0d6e6de63697" />


**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

