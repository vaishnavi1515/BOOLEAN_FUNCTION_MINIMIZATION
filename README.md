# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.



**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
Boolean Algebra is a branch of algebra that deals with boolean values—true and false. It is fundamental to digital logic design and computer science, providing a mathematical framework for describing logical operations and expressions

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
~~~
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
~~~


Developed by:vaishnavi V

RegisterNumber:24900560


**RTL**
F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

![experiment 2 f1](https://github.com/user-attachments/assets/614c0704-4e55-4a8a-81b7-c05dcfa1da43)

F2=xy’z+x’y’z+w’xy+wx’y+wxy
![experiment 2 f2](https://github.com/user-attachments/assets/2f16e1f2-d827-48fe-802c-2b4de8cf3d74)

**Output:**
F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

 ![exp 2 f1 output](https://github.com/user-attachments/assets/44f677ed-1112-47b5-bd33-9304fb41b9f7)
 
F2=xy’z+x’y’z+w’xy+wx’y+wxy
![exp 2 f2 output](https://github.com/user-attachments/assets/0bd43f2d-0dac-4740-bfbc-503e09dcff35)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

