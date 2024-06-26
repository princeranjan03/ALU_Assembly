# ALU_Assembly
An Arithmetic Logic Unit (ALU) implementation in 8086 Assembly Language that enables users to input numerical values, select desired arithmetic operations, and obtain the results. This program can perform basic arithmetic functions such as addition, subtraction, multiplication, and division, as well as advanced operations like modulus, squaring, and cubing. It also supports binary operations such as bitwise shifts, including rotate left (ROL) and rotate right (ROR), for enhanced data manipulation and flexibility in computation.

## Title:
ALU_Computation_8086



## Objective:
The aim of this project is to apply the concepts and knowledge of assembly language in a practical setting. It leverages what I've learned about various assembly instructions and applies them to the project. This allows me to gain a deeper understanding of instruction operations and assembly language coding using the EMU8086 emulator.


## Theory:
The calculator I've built performs simple mathematical operations such as addition, subtraction, multiplication, and division. It can also change a number's sign with the NEG operation, find the modulus, and conduct binary operations like OR, AND, XOR, and NOT. Additionally, it supports bitwise rotation operations (ROL and ROR), and can calculate the square and cube of a given number.


## Implementation:

I used EMU8086.inc Library which provides built in functions such as:<br>
print ‘STRING’ – For printing String<br>
scan_num – For taking Integer Input<br>
print_num – For displaying value stored in register<br>
printn – For printing New Line <br>
0dh and 0ah as well as print10 and print13 can also be used to move to new line.

## Debugging-Test-Run
EMU8086 emulator code interface
![image](https://github.com/princeranjan03/ALU_Assembly/blob/main/outputs/Screenshot%202024-04-27%20at%2012.41.39%E2%80%AFPM.png)<br><br>
Assembled code interface
![image](https://github.com/princeranjan03/ALU_Assembly/blob/main/outputs/Screenshot%202024-04-27%20at%2012.41.50%E2%80%AFPM.png)<br><br>
Output interface
![image](https://github.com/princeranjan03/ALU_Assembly/blob/main/outputs/Screenshot%202024-04-27%20at%2012.42.15%E2%80%AFPM.png)<br><br>
Addition Operation (+)
![image](https://github.com/princeranjan03/ALU_Assembly/blob/main/outputs/Screenshot%202024-04-27%20at%2012.44.45%E2%80%AFPM.png)<br><br>
Rotate left [ROL] Operation (<-)
![image](https://github.com/princeranjan03/ALU_Assembly/blob/main/outputs/Screenshot%202024-04-27%20at%2012.45.55%E2%80%AFPM.png)<br><br>
And Operation (&)
![image](https://github.com/princeranjan03/ALU_Assembly/blob/main/outputs/Screenshot%202024-04-27%20at%2012.46.40%E2%80%AFPM.png)<br><br>
Halted interface
![image](https://github.com/princeranjan03/ALU_Assembly/blob/main/outputs/Screenshot%202024-04-27%20at%2012.46.54%E2%80%AFPM.png)<br><br>
Thank You!! (end interface)
![image](https://github.com/princeranjan03/ALU_Assembly/blob/main/outputs/Screenshot%202024-04-27%20at%2012.47.03%E2%80%AFPM.png)<br><br>
